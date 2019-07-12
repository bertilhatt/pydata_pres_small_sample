# AB-testing on a small number of clusters
## PyData London 2019 - Tutorial

This repository contains a presentation tutorial drafted for [PyData London 2019](https://pydata.org/london2019/schedule/presentation/24/). We look into AB-testing, also known as Randomised-control trials (RCT) — notably issues raised by testing on small samples. We consider testing under constraints, typically having to segment users along groups or clusters of users.

### Stucture

This presentation covers principles of AB-tests, how to compute AA-tests and sensitivity tests and how to interpret insights from them. We then investigate complications from constraints. The most common type  restriction is that users belonging to a same group have to be exposed to the same experience, therefore in the same segment (known as Control and Treatment). This _de facto_ reduces the size of the sample to the number of clusters.  We consider the impact of testing on a sample of small size throughout.

The repository uses a table of `events` and `segment` randomly generated to illustrate our points. However, we encourage people to use their own dataset to understand how tests could work on their own data.

### Status

Both presenter were employees of [Farfetch](https://www.farfetchtechblog.com/en/) at the time of drafting and when presenting this tutorial. This presentation was made for educational purposes exclusively. No confidential information or code used by Farfetch is contained in this work. 

A video recording of this presentation should be make available by [the organisers](https://www.youtube.com/watch?v=J8cVPXnafos) of PyData London on [their YouTube channel](https://www.youtube.com/channel/UCOjD18EJYcsBog4IozkF_7w) after the conference.

Contributions are welcome. Re-use of the code is encouraged. Usual disclaimers apply.

The [slides](https://github.com/bertilhatt/pydata_pres_small_sample/blob/master/AB-testing%20by%20clusters%20-%20PyData%20London%202019%20Tutorial%20-%20Bertil%20Hatt%20%26%20Jo%C3%A3o%20Martins.slides.html) are generated using  the [`jupyter nbconvert`](https://nbconvert.readthedocs.io/) tool.

### Requirements

`pip install -r requirements.txt`

