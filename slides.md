---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Sample slides
#### PlaceHolderName
#### Universiti Malaysia Perlis
#### [placeholder@email.com](mailto:placeholder@email.com)

<!-- __AUDIO_INTRO_DO_NOT_TOUCH__ -->

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Slide one
**Key Concepts:**
- Energy conservation per @carnot1824.
- $\Delta U = Q - W$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics:

$$\Delta U = Q - W$$

The work done $W$ is positive when the system expands against an external pressure.
:::

::: {.column width="50%"}
<video data-src="media/videos/sample.mp4" data-autoplay loop muted width="100%"></video>
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 1 Control Analysis
**Parameters:**
- Pressure: 200kPa | Temp: 338K
- Mean: 49.77
- Spec: [45, 55]

Stability is assessed via the I-Chart generated in the previous step.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/control_m1.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 1 Process Capability
**Statistical Summary:**
- **Calculated Cpk: 1.246**
- **Status: NOT CAPABLE (Cpk < 1.33)**

As defined in [@carnot1824], efficiency depends on environmental constraints and process stability.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/capability_m1.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 2 Control Analysis
**Parameters:**
- Pressure: 200kPa | Temp: 338K
- Mean: 48.73
- Spec: [45, 55]

Stability is assessed via the I-Chart generated in the previous step.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/control_m2.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 2 Process Capability
**Statistical Summary:**
- **Calculated Cpk: 0.902**
- **Status: NOT CAPABLE (Cpk < 1.33)**

As defined in [@carnot1824], efficiency depends on environmental constraints and process stability.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/capability_m2.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 3 Control Analysis
**Parameters:**
- Pressure: 200kPa | Temp: 338K
- Mean: 51.08
- Spec: [45, 55]

Stability is assessed via the I-Chart generated in the previous step.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/control_m3.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 3 Process Capability
**Statistical Summary:**
- **Calculated Cpk: 0.937**
- **Status: NOT CAPABLE (Cpk < 1.33)**

As defined in [@carnot1824], efficiency depends on environmental constraints and process stability.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/capability_m3.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::
