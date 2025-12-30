# To-Be Process Map: Widget Assembly

## Improved State Flowchart (with Just-in-Time Staging)

1. [Start] Receive Raw Materials
2. --> Step 1: Cut Parts (CNC Machine)
3. --> Step 2: Assemble Sub-component A (Manual Station)
4. --> Step 3: Buffer & Stage Sub-component A (NEW)
   - *Purpose:* Hold a small, ready inventory of Sub-component A at the Final Assembly station to eliminate waiting time.
   - *Implementation:* Install a gravity‑feed rack that holds up to 5 sub‑components; replenished by a kanban signal.
5. --> Step 4: Final Assembly (Manual Station)
   - *Change:* Operators now pick pre‑staged, aligned sub‑components directly from the rack, eliminating misalignment errors.
6. --> Step 5: Quality Inspection (Visual Check + Go/No‑Go Gauge)
   - *Improvement:* Use a simple alignment gauge to catch any residual misalignment before the widget leaves the station.
7. --> Step 6: Pack and Label
8. --> [End] Ship Finished Product

## Process Details After Improvement

- **Cycle Time Target:** 100 minutes (≈17% reduction)
- **Defect Rate Target:** <5% (down from 15%)
- **Eliminated Bottleneck:** Waiting time between Sub‑component A assembly and Final Assembly reduced to near zero.
- **Key Enablers:** Kanban system, gravity‑feed rack, operator training on gauge use.

## Value Stream Mapping (Projected)

| Process Step | Value-Added? | Time (min) |
|--------------|--------------|------------|
| Cut Parts    | Yes          | 15         |
| Assemble Sub‑component A | Yes | 25 |
| Buffer & Stage | No (necessary non‑value) | 2 |
| Final Assembly | Yes       | 25 (reduced due to better alignment) |
| Quality Inspection | Yes | 8 (faster with gauge) |
| Rework       | No (necessary) | 5 (expected reduction) |
| Pack & Label | Yes          | 5 |

**Total Lead Time:** 105 minutes (↓ from 125)  
**Total Value‑Added Time:** 78 minutes (↑ from 72)  
**Process Efficiency:** 74% (↑ from 72%)

## Expected Benefits

1. **Quality:** Defect rate reduced from 15% to <5%.
2. **Speed:** Cycle time reduced by 20 minutes (≈17%).
3. **Cost:** Rework labor cut by 66%, material waste reduced.
4. **Morale:** Operators experience smoother workflow and less frustration.

## Implementation Notes

- The staging rack should be positioned within arm’s reach of the Final Assembly operator.
- A two‑bin kanban system will trigger replenishment when the first bin is empty.
- All operators must be trained on the new workflow and the use of the alignment gauge.
- Monitor performance for two weeks after implementation and adjust as needed.