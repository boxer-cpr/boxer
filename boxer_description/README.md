boxer_description
====================

This package contains the URDF files and STLs that make up the Boxer 2.4's description.

Note that Boxer 2.4's description can be customized using the following environment variables:

| Variable             | Default Value | Description                                                        |
|----------------------|---------------|--------------------------------------------------------------------|
| `BOXER_URDF_EXTRAS`  | `empty.urdf`  | Used to add additional links and joints to the URDF                |
| `BOXER_PC`           | `1`           | Set to `0` to remove the backpack PC from the URDF                 |
| `BOXER_PC_MODEL`     | `evs-2000`    | Customize the model of backpack PC.  Requires `BOXER_PC` to be `1` |

Supported `BOXER_PC_MODEL` values:
- `evs-2000` -- the Vecow EVS-2000 series industrial PC with GPU
- `mini-itx` -- generic mini-ITX form-factor PC with standard enclosure
