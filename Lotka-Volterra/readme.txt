--------------------------
Lotka-Volterra Folder
--------------------------

lotka_volterra - unprocessed equation with constant rows present
lotka_volterra_simple, lotka_volterra_second, varcon_lotka_volterra_second - x(t)-x(t-1)/dt used, processed version of initial eqn
        
    o lotka_volterra_simple - dataset: {𝑎.𝑥(𝑡−1), −𝒃/𝒂.𝑥(𝑡−1), (𝑥(𝑡)− 𝑥(𝑡−1))/𝑑𝑡}
    o lotka_volterra_second - dataset: {a, b, x.(t-1), y.(t-1), (𝑥(𝑡)− 𝑥(𝑡−1))/𝑑𝑡}
    o varcon_lotka_volterra_second - same dataset, values of a and b varied every ~1000 values.

Note: Code cells to generate relevant dataset files (.txt), code cells to process dataset files into readable arrays (PySR, GPLearn only) present in all notebooks