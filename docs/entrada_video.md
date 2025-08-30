# The First Spark: Bringing the Video Signal to the CRT

With the motherboard now installed, we faced one of the biggest challenges of the project: how to connect a modern PC to a 90s television? It was a true clash of technological generations.

## The Bridge Between Two Worlds: The Adapter

The problem was clear:

  - **The PC:** Offered a composite video output (AV).
  - **The Television:** Only had a **SCART (Euroconnector)** input.

The solution was an adapter that would act as a translator between both worlds: a SCART to AV (RCA) converter. This small device would be the key to sending the video signal directly from the graphics card to the heart of the cathode-ray tube.

```{image} /_static/img/7.png
:width: 400px
:align: center
:alt: SCART to RCA (AV) adapter for the video signal
```

### Adjustments to the case

As expected, the modern connectors did not fit into the old slots. We had to make a couple of modifications:

1.  **Graphics card output:** The original slot was too small for the video connector, so we had to **enlarge it**.

<!-- end list -->

```{image} /_static/img/33.jpeg
:width: 400px
:align: center
:alt: new hole
```

2.  **SCART port:** The SCART adapter itself was too bulky and also didn't fit into the slot, so we also had to **enlarge it**.

<!-- end list -->

```{image} /_static/img/27.jpeg
:width: 400px
:align: center
:alt: new scart hole
```

### We have a signal\!

After the adjustments, the moment of truth arrived: the first video test. **The result was a success**. The screen showed the Recalbox boot sequence, the first sign that the project was on the right track.

*(Note: In the photo, the board is outside because we took the opportunity to change its thermal paste).*

```{image} /_static/img/9.png
:width: 400px
:align: center
:alt: Correct signal
```
