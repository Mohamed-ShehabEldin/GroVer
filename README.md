# Grover's Algorithm Implementation and Success Probability Dependence On Grover's Iterates
### Outline
<br>
Part 1: General Grover's Algorithm
<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.1. Initialization
<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.2. Amplitude Amplification: Question some elements (winners)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.3. Amplitude Amplification: Boosting winners amplitudes
<br>
<br>
Part 2: Success Probability Dependence On Grover's Iterates
<br>
&nbsp;&nbsp;&nbsp;&nbsp;2.1. At constant number of winners (M=1)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;2.2. At constant number of Qubits (n=8, N=$2^8$)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;2.3. The Conclusive Equation
<br>

## Plots and Result

<div style="text-align:center"><img src="res1.png" width="400" /></div>
<div style="text-align:center"><img src="res2.png" width="400" /></div>
$$
\boxed{\boxed{ P_{success}(N,M,t) \approx  sin^2\left( 2\sqrt{\frac{M}{N}} \;t \right)}}
$$
<strong>
$P_{success}$: The probability of getting the right result.
<br>  
N: Length of the list.
<br>
M: Number of winners/solutions.
<br>
t: Number of Grover's iterates. (# amplitude amplifications).
<strong/>
