# Checkpoint-Based-Fault-Recovery-in-E-Health-Systems

# SAMPLE OUTPUT

[Checkpoint] System state saved successfully.

--- Iteration 1 ---
Current patient data: {'P001': {'heart_rate': 70, 'bp': '120/80'}, 'P002': {'heart_rate': 84, 'bp': '130/90'}, 'P003': {'heart_rate': 69, 'bp': '110/70'}}
[Checkpoint] System state saved successfully.

--- Iteration 2 ---
Current patient data: {'P001': {'heart_rate': 71, 'bp': '120/80'}, 'P002': {'heart_rate': 86, 'bp': '130/90'}, 'P003': {'heart_rate': 70, 'bp': '110/70'}}

[Error] System crash detected!
[Recovery] System recovered from last checkpoint.

--- Iteration 3 ---
Current patient data: {'P001': {'heart_rate': 72, 'bp': '120/80'}, 'P002': {'heart_rate': 85, 'bp': '130/90'}, 'P003': {'heart_rate': 68, 'bp': '110/70'}}
[Checkpoint] System state saved successfully.
...
[System] Monitoring completed successfully.
