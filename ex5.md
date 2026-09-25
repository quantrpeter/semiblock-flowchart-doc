# Exercise 5 — Smart Light System

## Task

Design a flowchart for a simple automatic light system.

The system detects whether the environment is dark.

If it is dark:

> Turn the light ON

If it is not dark:

> Turn the light OFF

After checking the light level, the system should check again.


## Requirement

Use:

- **Start/End**
- **Input**
- **Decision**
- **Process**
- **Arrow**


## Suggested Logic

|  |  |  |
| :---: | :---: | :---: |
|  | Start |  | 
|  | ↓ |  | 
|  | Read light sensor |  |
|  | ↓ |  |
|  | Is it dark? |  |
| Yes ↙ |  | ↘ No |
| Light ON |  | Light OFF |
| ↘ |  | ↙ |
|  | Read light sensor again |  | 


## Challenge

Add another condition:

If a person is detected **and** it is dark, turn the light ON.

Otherwise, keep the light OFF.

### Click here to check the answer -> [Answer]()