# Perk-Distribution-Webtool
Perk Distribution Application[COL749]
# Perks-Fair: Envy-Free Perks Distribution Toolkit

Perks-Fair is a lightweight web app that computes **envy-free up to one item (EF1)** allocations of indivisible perks (e.g. parking spots, gadgets) among employees, and calculates the **minimal monetary subsidies** needed to eliminate all envy (at most \$1 per person).

---

## Features

- **Allocate & Pay**  
  - Upload a CSV of employee×perk valuations  
  - Compute an EF1 assignment via round-robin max-weight matching  
  - Derive the smallest envy-eliminating payments in one click  

- **Payments Only**  
  - Given any envy-freeable assignment + the same CSV valuations  
  - Compute the minimal subsidies for each employee  

- **UI Highlights**  
  - Modern purple theme, responsive cards  
  - File-upload drag-zone & manual JSON entry  
  - Loader animations & polished distribution report  

---

## Quickstart

1. **Clone & Install**  
   ```bash
   git clone https://github.com/your-org/perks-fair.git
   cd perks-fair/backend
   python -m venv venv
   source venv/bin/activate    # Windows: venv\Scripts\activate
   pip install -r requirements.txt
