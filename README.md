## **Model Name and Serial Number**

**1.** Open Airoha app

**2.** MCSYNC FOTA UT

**3.** Add the same .nvr file to the 'Left' and 'Right' NVR channels

**4.** Update NVR

## **Getting your Serial Number**

**1.** Write down the 10 digit serial number specified on the lid of the AirPods Case <span style="color: yellow"> ⚠️ **COPY CAPITALIZED LETTERS** </span>

**2.** Convert to **Hex**
https://www.rapidtables.com/convert/number/ascii-to-hex.html

- **Example:** Serial Number - JY45H3FT9D

  - Converted to Hex - `4A 59 34 35 48 33 46 54 39 44`
  - <span style="color: red"> **Remove all spaces and turn uppercase letters into lowercase** </span> = `4a593435483346543944`

**3.** Open `serial.nvr` in **VSCode** or **Notepad++** and add the **Hex** to lines 2 and 3

- `&0xFB01 = 4a593435483346543944`
- `&0xFB11 = 4a593435483346543944`
