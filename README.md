# ASRI Lobby Dataset
A real-world dataset collected by LDS laboratory through data collection at the Seoul National University ASRI building lobby.
## Overview
**◦ Autonomous Pedestrian trajectory Data Collection**
- Collection of data gathered from three different lidars positioned strategically within the lobby to record all moving obstacles within the lobby without blind spots.
## Datasets version

### Key Application
```pedestrian trajectory prediction```,  ```situation awareness```, ```drivability assessment```, ```safety related controller test```,```etc```

### Dataset Characteristics
**◦ Volume of Dataset**

### Labels
**◦ Data Format**
- Simple X and Y coordinates for every single moving object detected during the recording with relevant automatic agent number assignment.
- Each line in the CSV files are split into four columns consisting of Frame,Agent_ID,X,Y.

| Frame | Agent_ID | X                | Y                  |
|------:|---------:|------------------:|-------------------:|
| 1     | 1        | 2.0540540540540526 | -2.6799999999999997 |
| 1     | 2        | 7.513513513513516  | -1.213333333333333  |
| 2     | 1        | 2.0540540540540526 | -2.6533333333333333 |
| 2     | 2        | 7.54054054054054   | -1.1866666666666674 |
| 3     | 1        | 2.0540540540540526 | -2.6799999999999997 |
| 3     | 2        | 7.567567567567568  | -1.1333333333333329 |
| 4     | 1        | 2.0540540540540526 | -2.6533333333333333 |

## Citing Datasets

If you use **this datasets** in your research, please use the following BibTeX entry.

``` bibtex
@misc{joonhohan2025robot,
  author =       {Joonho Han},
  title =        {SNU-ASRI dataset},
  howpublished = {\url{[https://github.com/CORE-SNU/Pedestrian-Trajectory-Dataset](https://github.com/CORE-SNU/Pedestrian-Trajectory-Dataset)}},
  year =         {2025}
}
```

---

Please email <snowhan1021@snu.ac.kr> to report any issues.
