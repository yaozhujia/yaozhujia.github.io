---
layout: page
title: Eiffel
description: Eiffel is a tool used to detect significant floating-point errors. Instead of search such significant floating-point errors, Eiffel infers the input ranges that triggers such errors via polynomial extrapolation. The input ranges inferred by Eiffel can work with program rewrite engines like Herbie.
img: assets/img/eiffel-arch.png
importance: 1
category: Numerical Program Analysis
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/eiffel-arch.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The architecture decipts how Eiffel works, and the open-source repository is available at <a href='https://github.com/zuoyanzhang/Maxfpeed'>GitHub</a> maintained by the primary author <a href='https://zuoyanzhang.github.io/'>Zuoyan Zhang</a>. The related paper was published and presented at <a href='https://dl.acm.org/doi/10.1109/ASE56229.2023.00139'>ASE 2023</a>.
</div>
