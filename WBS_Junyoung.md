# AlphaD Junyoung

## WBS Table

- Dep is short for Dependency.
- Sh.T, St.T, Lo.T, Avg.T, V are short for Shortest Time, Standard Time, Longest Time, Average Time, Variant each.
- H, M are short for Hour(60M), Minuit unit each.

| #Task | Task Detail                      | Dep        | Description                                                      | Sh.T | St.T | Lo.T | Avg.T   | V      |
|:-----:|----------------------------------|:----------:|------------------------------------------------------------------|-----:|-----:|-----:|--------:|-------:|
| Z     | WBS Writing                      | -          | Writing WBS                                                      | 3H   | 4H   | 5H   | 4H      | 20M    |
| A     | Computer Assembly & Setting      | -          | Assembly each parts and install OS & Utilities.                  | 18H  | 30H  | 42H  | 30H     | 4H     |
| B     | Computer Setting Explanation     | A          | Write explanation about __A__.                                   | 6H   | 12H  | 18H  | 12H     | 2H     |
| C     | Machine Learning Documentation   | -          | Collecting and ordering documents about ML, especially GA.       | 20H  | 40H  | 60H  | 40H     | 6H 40M |
| D     | Gazebo Learning                  | -          | Learn how to simulate a drone on Gazebo.                         | 3H   | 5H   | 7H   | 5H      | 40M    |
| E     | Gazebo Simple Explanation        | D          | Write Simply about Gazebo simulation.                            | 2H   | 3H   | 4H   | 3H      | 20M    |
| F     | Drone Test                       | -          | Test real drone for simulation setting.                          | 20H  | 28H  | 36H  | 28H     | 2H 40M |
| G     | Simulation Stack Setting         | A, D, F    | Setting gazebo to simulate our drone.                            | 20H  | 28H  | 36H  | 28H     | 2H 40M |
| H     | Write Mid Report                 | B, C, E, G | Write Mid Report about simulation setting for GA.                | 10H  | 14H  | 18H  | 14H     | 1H 20M |
| I     | Specify 1st Fitness Function     | G          | Decide 1st Fitness Function for GA.                              | 1H   | 24H  | 47H  | 24H     | 4H 20M |
| J     | Specify 1st Gene                 | G          | Decide 1st Gene for GA.                                          | 1H   | 24H  | 47H  | 24H     | 4H 20M |
| K     | Specify 1st Crossover Method     | G          | Decide 1st Crossover method for GA.                              | 1H   | 24H  | 47H  | 24H     | 4H 20M |
| L     | Specify Other details            | I, J, K    | Decide 1st Mutation method, 1st Selection method, etc... for GA. | 4H   | 12H  | 20H  | 12H     | 2H 40M |
| M     | 1st GA Try                       | L          | Try GA with 1st GA setting set.                                  | ?    | ?    | ?    | ?       | ?      |
| N     | 1st GA Try Documentation         | M          | Write explanation about GA 1st try.                              | 4H   | 4H   | 4H   | 4H      | 0      |
| O     | Repeat Until Success             | M          | Repeat __I__ - __N__ until success or only tight time left.      | ?    | ?    | ?    | ?       | ?      |
| P     | Collecting Real Data             | O          | Collecting real data using simulation result and drone.          | 10H  | 20H  | 30H  | 20H     | 3H 20M |
| Q     | Analyzing Data                   | P          | Analyze data and prettify.                                       | 20H  | 40H  | 60H  | 40H     | 6H 40M |
| R     | Analyzing Method Documentation   | Q          | Write explanation about analyzing and prettifying methods.       | 4H   | 6H   | 8H   | 6H      | 40M    |
| S     | Organizing References And Others | H, N, R    | Collect and organize reperences, data, etc... for final report.  | 10H  | 15H  | 20H  | 15H     | 1H 40M |
| T     | Write Final Report               | S          | Write final report.                                              | 20H  | 28H  | 36H  | 28H     | 2H 40M |

## WBS Calender

### June-July

| Sun           | Mon           | Tue           | Wed           | Thu           | Fri           | Sat           |
|---------------|---------------|---------------|---------------|---------------|---------------|---------------|
| 26            | 27            | 28            | 29            | 30            | 1             | 2             |
| Z             | Z             |               |               |               | A             | A             |
| 3             | 4             | 5             | 6             | 7             | 8             | 9             |
| A & B         | A & B         | B             | C             | C & D         | C & D         | C & E         |
| 10            | 11            | 12            | 13            | 14            | 15            | 16            |
| C             | C             | C & F         | F             | F             | F & G         | F & G         |
| 17            | 18            | 19            | 20            | 21            | 22            | 23            |
| F & G         | F & G         | F & G         | F & G         | H             | H             | H             |
| 24            | 25            | 26            | 27            | 28            | 29            | 30            |
| I & J & K     | I & J & K     | I & J & K     | L             | L             | M & N         | M & N         |
| 31            |               |               |               |               |               |               |
| M & N         |               |               |               |               |               |               |

### August

| Sun           | Mon           | Tue           | Wed           | Thu           | Fri           | Sat           |
|---------------|---------------|---------------|---------------|---------------|---------------|---------------|
|               | 1             | 2             | 3             | 4             | 5             | 6             |
|               | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     |
| 7             | 8             | 9             | 10            | 11            | 12            | 13            |
| M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     |
| 14            | 15            | 16            | 17            | 18            | 19            | 20            |
| M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     |
| 21            | 22            | 23            | 24            | 25            | 26            | 27            |
| M & N & O     | -             | -             | -             | -             | -             | -             |
| 28            | 29            | 30            | 31            |               |               |               |
| -             | -             | -             | -             |

### September

| Sun           | Mon           | Tue           | Wed           | Thu           | Fri           | Sat           |
|---------------|---------------|---------------|---------------|---------------|---------------|---------------|
|               |               |               |               | 1             | 2             | 3             |
|               |               |               |               | -             | -             | M & N & O     |
| 4             | 5             | 6             | 7             | 8             | 9             | 10            |
| M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     | M & N & O     |
| 11            | 12            | 13            | 14            | 15            | 16            | 17            |
| P             | P             | P             | P & Q         | Q             | Q             | Q             |
| 18            | 19            | 20            | 21            | 22            | 23            | 24            |
| Q             | Q & R         | Q & R         | R             | S             | S             | S             |
| 25            | 26            | 27            | 28            | 29            | 30            |               |
| T             | T             | T             | T             | T             | T             |               |

