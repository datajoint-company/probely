# Probely

Single Probe Design with Emitters

```python
from probely import Probe

# Create design
P = Probe(
    probe_dimensions=[1200, 120, 1300],
    n_e_box=[5, 60],
    e_box_length=10,
    e_box_sep=10,
    e_box_vertical_margin=5,
    e_box_horizontal_margin=15,
    n_d_box=[0, 0],
    d_box_length=0,
    d_box_sep=0,
    d_box_vertical_margin=0,
    d_box_horizontal_margin=0,
    name="P1",
)
```

To plot the probe in 2D:

```python
P.plot2d(show=True)
```

![Single Probe 2D](images/SingleProbeemitteronly.png)


To plot the probe in 3D:

```python
P.plot3d(show=True)
```

# Installation
```
pip install probely
```