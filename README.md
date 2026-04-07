What the model does?
The simulator solves a system of coupled differential equations (Model v5) describing how a basaltic magma chamber cools, crystallizes, and chemically evolves into trachyte over tens of thousands of years. It reproduces the four observed eruption sequences (oldest to newest):
seq_#  Name                 Observed age
Seq 1  Trachyte of Gura 3   ~142 ka
Seq 2  Trachyte of Matan    ~122 ka
Seq 3  Trachyte of Gura 2   ~94 ka
Seq 4  Trachyte of Mouteen  ~32 ka

Features:
-Full geological cross-section animation — mantle → crust → magma chamber → conduit → volcano
-Live temperature, SiO₂, and crystal fraction tracking
-Per-sequence adjustable parameters: cooling rate (Kc), basalt temperature, ambient temperature, AFC ratio
-All Sequences and Individual playback modes
-Eruption timeline with dormancy gaps
-Fully self-contained single HTML file — no dependencies, no server needed

Physics:
-Cooling equation with latent heat feedback (dynamic L/Cp = 270.3°C)
-Six mineral phases: olivine, clinopyroxene, plagioclase, magnetite, alkali feldspar, residual melt
-Assimilation and Fractional Crystallization (AFC) process
-Model validated against USGS-observed eruption timescales

