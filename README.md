# Permissionless Blockchain: Recent Trends, Privacy Concerns, Potential Solutions, and Secure Development Lifecycle

This repository contains the supporting materials for the review paper submitted to *MDPI Future Internet*.

## Structure
- **/diagrams/mermaid/** – Mermaid diagram source files (`.mmd`) for conceptual and architectural figures.  
- **/diagrams/python/** – Python scripts used to generate charts included in the paper.  
- **/diagrams/python/outputs/** – Rendered charts (PNG/SVG) generated from the scripts.  
- **/data/** – Small example data files (CSV/JSON) used for the visualizations.  
- **/docs/** – Citation file, reference mapping, and license information.

## Usage
To reproduce or view the figures:

```bash
# Render Mermaid diagram
mmdc -i diagrams/mermaid/fig1_architecture_layers.mmd -o fig1_architecture_layers.png

# Run Python chart
python diagrams/python/fig4_research_trends.py
