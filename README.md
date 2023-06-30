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
    - :white_check_mark: `Powershell`, disabling interface, automation via Windows Scheduler, trigger: `time`, logic: `path`;
    - 🕒 `Powershell`, disabling interface, automation via Windows Scheduler, trigger: `time`, logic: `process`;
    - 🕒 `Powershell`, enabling false-proxy, automation via Windows Scheduler, trigger: `time`, logic: `path`;
    - 🕒 `Powershell`, enabling false-proxy, automation via Windows Scheduler, trigger: `time`, logic: `process`;
    - 🕒 `Python 3`, automation via Windows Scheduler, trigger: `n/a`, logic: `path`;
    - _in progress..._
  - **Unix-based**
    - 🕒 Bash, automation via `cron`, trigger: `n/a`, logic: `path`;
    - 🕒 Bash, automation via `cron`, trigger: `n/a`, logic: `process`;
    - 🕒 `Python 3`, automation via `cron`, trigger: `n/a`, logic: `path`;
    - 🕒 `Python 3`, automation via `cron`, trigger: `n/a`, logic: `process`;
    - _in progress..._
