# Day 34 – RAID (Redundant Array of Independent Disks)

## What is RAID?

RAID stands for Redundant Array of Independent Disks.
It combines multiple physical disks into a single logical storage unit.

Goals:
- Improve performance
- Provide redundancy
- Increase availability

---

## Common RAID Levels

### RAID 0 – Striping
- High performance
- No redundancy
- If one disk fails, all data is lost

### RAID 1 – Mirroring
- Exact copy of data
- High redundancy
- Good fault tolerance

### RAID 5 – Striping with Parity
- Requires minimum 3 disks
- Balanced performance + redundancy
- Can survive one disk failure

### RAID 10 – (1+0)
- Combination of RAID 1 and RAID 0
- High performance
- High redundancy
- Used in enterprise systems

---

## Why RAID Matters in Cybersecurity

- Prevents data loss
- Ensures business continuity
- Important for disaster recovery
- Used in servers and data centers

---

## Why It Matters

RAID is critical for availability, fault tolerance, and infrastructure security.
Understanding RAID helps in designing resilient systems.
