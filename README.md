# MUDE-PD



Logs from MUDE-PD scenarios simulations executed in GrADyS-SIM NextGen, a Python framework designed to simulate distributed algorithms in a network environment comprising communication and mobile nodes. GrADyS-SIM NextGen enhances the original GrADyS-SIM framework \cite{Lamenza:22-Gradys, gradys_github} by allowing users to simulate the same code in both integrated modes using OMNeT++ \cite{OMNET:22} for more realistic simulations of network interactions. This framework was employed to model and observe the movement and message exchanges of UAV swarms, thereby validating communication and cooperation among UAVs, ground stations, and mobile PoIs.

A comprehensive set of scenarios was modeled to assess the effectiveness of the MUDE-PD search algorithm across various parameter configurations as presented in the table bellow. 

\begin{table}[!h]
    \centering
    \caption{All values that are used to define each simulation scenario.}
    \label{tab:simulation_values}
    \begin{tabularx}{\columnwidth}{l c c c}
        % \hline
          & & \textbf{Values} & \textbf{Unit}\\ 
         \hline
         \multirow{4}{*}{\textbf{Environment Parameters}} & $A$ & 16, 36, 64 & hectares\\
         & $k$ & 1, 2, 8, 16, 50, 100 & units\\
         & $c_k$ & 0, 1, 5, 10 & clusters\\
         & $v_o^+$ & 5 & m/s \\
         \hline
         \multirow{8}{*}{\textbf{Mission Parameters}} & $n^+$ & 2, 4, 8, 16, 32, 64 & units\\
         & $N_S$* & 2, 4, 8, 16, 32, 64 & units\\
         & $N_I$* & 2, 4, 8, 16, 32, 64 & units\\
         & $N_R$* & 2, 4, 8, 16, 32, 64 & units\\
         & $T$ & 900, 1200, 1800 & seconds \\
         & $r_c$ & 20 & meters \\
         & $h$ & 20 & meters \\
         & $v$ & 10 & m/s \\
         \hline
         \multicolumn{4}{c}{\footnotesize $+$ parameter exclusive to MUDE-PD \quad $*$ parameter exclusive to Yanmaz} \\
    \end{tabularx}
\end{table}

