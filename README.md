# Topo4MEC
Topology data for MEC networks

## File structure
- `TOPO_NAME`:
    - `TOPO_NAME.jpg` : network graph
    - `graph.txt`     : network graph data (edge-list format: [i, j, bandwidth])
    - `ingress.txt`   : ingress nodes

**Notice**:
Topology `MilanCityCenter` is generated based on the data from [**OpenCellID**](https://www.opencellid.org/), which is an open database of cell towers. We considered the Milan City Center area around Duomo. The others are random topologies generated with different numbers of nodes and edges.
