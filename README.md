
<!---
ed-mr/ed-mr is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

- $i_t = \sigma(x_t\times U^i+h_{t-1}\times W^i+B^i)$
- $f_t = \sigma(x_t\times U^f+h_{t-1}\times W^f+B^f)$
    $o_t = \sigma(x_t\times U^o+h_{t-1}\times W^o+B^o)$
    $\tilde C_t=tanh(x_t\times U^g+h_{t-1}\times W^g+B^g)$
    $C_t=f_t\circ C_{t-1}+i_t\circ \tilde C_t$
    $h_t = o^t\circ tanh(C_t)$


