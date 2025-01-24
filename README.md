## <a href="#model-name" id="model-name" name="model-name">**Model Name**</a>

**1.** Download the `.nvr` file from here for your model

**2.** Open the **AB1562_UT** app

**3.** MCSYNC FOTA UT

**4.** Add the same .nvr file to the 'Left' and 'Right' NVR channels

**5.** Update NVR

## <a href="#sn" id="sn" name="sn"> **Getting your Serial Number** </a>

**1.** Write down the 10 digit serial number specified on the lid of the AirPods Case <br>

- ⚠️ **COPY CAPITALIZED LETTERS**

**2.** Convert to **Hex**
https://www.rapidtables.com/convert/number/ascii-to-hex.html

- **Example:** Serial Number - JY45H3FT9D

  - Converted to Hex - `4A 59 34 35 48 33 46 54 39 44`
  - Remove all spaces and turn uppercase letters into lowercase = `4a593435483346543944`

**3.** Open `serial.nvr` in **VSCode** or **Notepad++** and add the **Hex** to lines 2 and 3

- `&0xFB01 = 4a593435483346543944`
- `&0xFB11 = 4a593435483346543944`

**4.** Follow **steps 2-5** in <a href="#model-name">**Model Name**</a>
