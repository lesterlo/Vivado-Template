# Vivado Project Template for version control

## Project Initialization

1. Start a new project under `Vivado_gen` folder


## Usage
1. Create a source file under `Source Data/`.

2. Generate the `.tcl` rebuild script after each modification via GUI. 

    a. For normal modification, Use `File -> Project -> Write TCL`

    b. For Block design modification`File -> Export -> Export Block Design`

    c. output Path should be `SourceData/Script/`

3. After clone / update the modification, run the rebuild script on the GUI console.
    ```
    source <path_to_your_script>.tcl
    ```

