# Routine: `wwKTEST1KTZ`

This ObjectScript routine (`wwKTEST1KTZ`) is used for performing various queries and updates on authorization master data stored in global variables (e.g., `^MKEN1KTZ`, `^MKEN2KTZ`, `^MDIC`, `^MSYA`).

## Prerequisites

- InterSystems IRIS or Caché environment set up and running
- Globals `^MKEN1KTZ`, `^MKEN2KTZ`, `^MDIC`, `^MSYA` loaded with proper data
- Appropriate access to the namespace/environment where this data is stored

## How to Run the Routine

1. **Start the Terminal**  
   Open your InterSystems terminal or Management Portal Terminal.

2. **Switch to the correct namespace** (if necessary):  
   ```objectscript
   ZN "YOURNAMESPACE"
    ```

3. **Compile all files**

4. **Load Sample Data by running LoadData.mac**
    ```objectscript
    do ^LoadData
    ```

5. **Run answer routine file**
    ```objectscript
    do Q1^wwKTEST1KTZ  (for question 1)
    ```
