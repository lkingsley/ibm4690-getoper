# Getoper

IBM 4680/4690 command line application to retrieve operators information.

## Compile

Compile the application with the IBM 4680/4690 Basic Compiler and link with the linker LINK86 Linkage Editor.
```bash
C:ADX_UPGM/BASIC GETOPER.BAS
```

```
C:ADX_UPGM/LINK86 GETOPER.OBJ
```

## Usage

Run the app inserting the operator id as an argument.
e.g:

```
C:ADX_UPGM/GETOPER.286 1234
```

Result:

```
OPERATOR: 0000001234
PASSWD:   0000001234
OPERNAME: LUIS KINGSLEY
OPTIONS:  01
USEREXIT: SALES FUNCTIONS
```
