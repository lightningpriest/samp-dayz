# Project DayZ - San Andreas Multiplayer
Remaintained version from [Project-DayZ-SAMP](https://github.com/AaronNader96/Project-DayZ-SAMP) repo.  
Applied small fixes, and optimizes.  
For whoever that can't compile from original source, here it is.  

## Required Dependencies
| Dependencies   | Link                                                   |
|----------------|--------------------------------------------------------|
| YSI v4.0.2      | https://github.com/pawn-lang/YSI-Includes/releases/download/v4.0.2/YSI.zip                  |  
| foreach v19.1  | https://github.com/karimcambridge/samp-foreach/releases/tag/v19.1 |

## Setup
- Make sure you have original copies from [here](https://github.com/AaronNader96/Project-DayZ-SAMP).
- Unpack, also you need to install [SA-MP 0.3.7](https://www.sa-mp.com/) client and server resources.
- Next, replace the original **dayz.pwn** with [this](https://github.com/rizzyneck/samp-dayz/blob/main/gamemodes/dayz.pwn).  
- Once all done, you need to configure the MySQL Connections for Database.  
- Delete **YSI** folder at pawno/include, replace with [YSI v4.0.2](https://github.com/pawn-lang/YSI-Includes/releases/download/v4.0.2/YSI.zip).
- Compile.

## Database Setup
- Open **dayz.pwn** then go to [line 37](https://github.com/rizzyneck/samp-dayz/blob/main/gamemodes/dayz.pwn#L37).  

## Important Notes
- Database are automatically created.  
- Update the foreach into the [latest version](https://github.com/karimcambridge/samp-foreach/releases/tag/v19.1).  
- Read [this](https://github.com/AaronNader96/Project-DayZ-SAMP/blob/master/README.md).  
- Open Issues or Pull Request are welcomed.

## Credits
[Aaron Nader](https://github.com/AaronNader96) for awesome gamemode.  
[Y-Less](https://github.com/Y-Less) for YSI Includes.  
[karimcambridge](https://github.com/karimcambridge) for samp-foreach.
