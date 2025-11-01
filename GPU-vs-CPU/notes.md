
Lec: https://www.youtube.com/watch?v=xdcW52tEPfE
<img width="1078" height="675" alt="Screenshot 2025-11-01 at 11 32 06 AM" src="https://github.com/user-attachments/assets/7bd0fe05-69b0-44d4-bd8e-7d631b54e34d" />

The CPU has a lot of control logic to decode and execute instructions. Execution does the calculation and cache layer is used as memory, general idea is in order to get a good performance you'd need to reduce the latency between layers. 

GPUs have many more executions units and also multiple control units. Key point is that large GPUs hsve a lot more execution layer which gives more throughput through these units by scheduling many parallel tasks.

<img width="1553" height="821" alt="Screenshot 2025-11-01 at 11 37 28 AM" src="https://github.com/user-attachments/assets/8d10f1e7-9bc9-471f-adee-c97f30d3561b" />

## GPU:

<img width="1359" height="815" alt="Screenshot 2025-11-01 at 12 00 59 PM" src="https://github.com/user-attachments/assets/08ae0cac-c470-499d-9336-aff5b8a5e32b" />

- SIMD: Single instruction multiple data, basically means small instruction which executes over a large dataset.
- GPU has higher memory bandwidth, so lot of GPU chsllenges is around optimising memory bandwidth.

## How GPU processes
<img width="1377" height="956" alt="Screenshot 2025-11-01 at 3 14 27 PM" src="https://github.com/user-attachments/assets/ff678e79-e668-4e80-890b-81ea38e1e566" />

