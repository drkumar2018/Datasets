This dataset contains 542 entries and 8 attributes, designed to capture key resource utilization metrics for virtual machines (VMs) in cloud environments. It is useful for workload prediction, resource allocation, and performance analysis using machine learning techniques.

Attributes:
timestamp (int)

Unix timestamp of the observation (seconds since epoch).

Example: 1722310800

cpu_usage_list (float)

CPU utilization as a percentage of total available CPU.

Range: 0–100 (%)

mem_usage_percent_list (float)

Memory utilization as a percentage of total available memory.

Range: 0–100 (%)

disk_read_list (float)

Amount of data read from disk.

Unit: Megabytes per second (MB/s)

disk_write_list (float)

Amount of data written to disk.

Unit: Megabytes per second (MB/s)

net_in_list (float)

Network input traffic.

Unit: Kilobytes per second (KB/s)

net_out_list (float)

Network output traffic.

Unit: Kilobytes per second (KB/s)

resource_id (string)

Unique identifier of the resource (VM instance).

Example: vm-25

Dataset Size:
Rows: 542

Columns: 8

Format: CSV (Comma-Separated Values)

Use Cases:
Cloud workload prediction

Resource optimization in virtualized environments

Performance monitoring dashboards

Anomaly detection in resource usage

Example Row:
sql
Copy
Edit
timestamp,cpu_usage_list,mem_usage_percent_list,disk_read_list,disk_write_list,net_in_list,net_out_list,resource_id
1722310800,45.23,61.87,120.55,87.42,543.11,231.54,vm-12
License:
This sample dataset is for educational and research purposes.

