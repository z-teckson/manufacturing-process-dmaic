# As-Is Process Map: Widget Assembly

## Current State Flowchart

1. [Start] Receive Raw Materials
2. --> Step 1: Cut Parts (CNC Machine)
3. --> Step 2: Assemble Sub-component A (Manual Station)
4. --> Step 3: Transport Sub-component A to Final Assembly (Conveyor)
5. --> Step 4: Wait for Parts Availability (Queue)
6. --> Step 5: Final Assembly (Manual Station)
7. --> Step 6: Quality Inspection (Visual Check)
8. --> Step 7: Rework Loop (if defects found)
9. --> Step 8: Pack and Label
10. --> [End] Ship Finished Product

## Process Details

- **Cycle Time:** 120 minutes average
- **Defect Rate:** 15% (mostly misalignment at Final Assembly)
- **Bottleneck:** Waiting time between Step 2 and Step 5 (up to 20 minutes)
- **Key Inputs:** Raw materials (metal sheets, fasteners)
- **Key Outputs:** Finished widgets, quality reports

## Value Stream Mapping Notes

| Process Step | Value-Added? | Time (min) |
|--------------|--------------|------------|
| Cut Parts    | Yes          | 15         |
| Assemble Sub-component A | Yes | 25 |
| Transport    | No (necessary) | 5 |
| Wait         | No           | 20         |
| Final Assembly | Yes       | 30         |
| Quality Inspection | Yes | 10 |
| Rework       | No (necessary) | 15 |
| Pack & Label | Yes          | 5 |

**Total Lead Time:** 125 minutes  
**Total Value-Added Time:** 90 minutes  
**Process Efficiency:** 72%