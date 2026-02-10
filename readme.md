# BSG Reinach – Logo Color Tool

A small static webpage to preview the BSG Reinach logo and try different color combinations.

## What you can do
- Switch between **Logo Variant A** and **Variant B**
- Switch between **Positiv** and **Negativ** versions
- Adjust the three main colors via color pickers (**Hell / Dunkel / Akzent**)
- Apply predefined color themes loaded from `palettes.csv`
- Download the current logo preview as a **PNG**

## palettes.csv
Preset themes are read from `palettes.csv` in the same folder as `index.html`.  

Required columns:

- `variant`
- `name`
- `bright`
- `dark`
- `highlight`

Example:

```csv
variant;name;bright;dark;highlight
01;Sonnengelb, Nachtblau, Signalrot;#F9C619;#24376C;#EC1F27
02;Mandarinorange, Petrolgruen, Kirschrot;#F79F24;#10696A;#EA232B