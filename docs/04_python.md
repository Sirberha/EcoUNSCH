---
layout: default
title: Python y la Matemática
nav_order: 2
has_children: true
---


# Ejecuta el Notebook Interactivamente

<button id="activate-button" onclick="thebelab.bootstrap()">Ejecutar el Notebook</button>

<div class="thebe-source">
    <pre data-executable="true" data-language="python">
# Aquí puedes escribir código Python que se podrá ejecutar
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 10, 100)
y = np.sin(x)

plt.plot(x, y)
plt.show()
    </pre>
</div>

<script src="https://unpkg.com/thebelab@latest/lib/index.js"></script>
<link rel="stylesheet" href="https://unpkg.com/thebelab@latest/lib/index.css">

<script type="text/x-thebe-config">
{
  requestKernel: true,
  binderOptions: {
    repo: "Sirberha/EcoUNSCH",
    ref: "master"
  }
}
</script>
