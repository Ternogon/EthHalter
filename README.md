# EthHalter
![EthHalter Banner](https://github.com/Ternogon/EthHalter/assets/31628014/220bde3f-43f4-439b-9c84-6c4eb4e0e083)
_Halter of Ethernet adapters which can be used for leakage confidential information._


## Description
A set of scripts (programs) to restrict access to the Internet from an automated control system that is not equipped with a specific control software that can monitor user actions on the Internet in more detail and/or counteract leaks of confidential information.

## Statuses
| Sign                  | Status                    |
|:---------------------:|---------------------------|
| :white_check_mark:    | Realised                  |
| 🕒 | In development            |
| :x:                   | Not working/supported     |

  - **Windows-based**
    - :white_check_mark: `Powershell`, disabling interface, automation via Windows Scheduler, trigger: `time`;
    - 🕒 `Powershell`, disabling interface, automation via Windows Scheduler, trigger: `opened webbrowser`;
    - 🕒 `Powershell`, enabling false-proxy, automation via Windows Scheduler, trigger: `time`;
    - 🕒 `Powershell`, enabling false-proxy, automation via Windows Scheduler, trigger: `opened webbrowser`;
    - 🕒 `Python 3`, automation via Windows Scheduler, trigger: `n/a`;
    - _in progress..._
  - **Unix-based**
    - 🕒 Bash, automation via `cron`, trigger: `n/a`;
    - 🕒 `Python 3`, automation via `cron`, trigger: `n/a`;
    - _in progress..._
