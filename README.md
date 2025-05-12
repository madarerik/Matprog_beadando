# Benzinár Elemzés – Python Jupyter Notebook

Ez a projekt a magyarországi és európai benzinárak időbeli alakulását vizsgálja különféle statisztikai módszerekkel és adatvizualizációs eszközökkel. A cél az adatok elemzése, trendek felismerése és vizuális megjelenítése Python segítségével.

## Fájlok

- `beadandó végleges.ipynb` – A Jupyter notebook, amely tartalmazza az adatok beolvasását, feldolgozását, elemzését és vizualizációját.

## Használt könyvtárak

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `bokeh`
- `scipy`
- `folium`
- `json`
- `requests`
  
## Bemeneti adatok

A kód két `.csv` fájlt használ:

1. `euro_petrol.csv` – Európai benzinárak.
2. `95_petrol_hu.csv` – Magyarországi benzinárak (forintban).

> **Fontos:** Az adatok elérési útját a saját gépeden kell megadni a következő sorokban:
```python
europe_df = pd.read_csv("IDE_ÍRD_AZ_ELÉRÉSI_UTAT/euro_petrol.csv")
hungary_df = pd.read_csv("IDE_ÍRD_AZ_ELÉRÉSI_UTAT/95_petrol_hu.csv")
```

## Futási környezet

- Python 3.8+
- Jupyter Notebook vagy JupyterLab

## Funkciók

- Adatok beolvasása és előfeldolgozása
- Árfolyamváltás forintról euróra
- Z-score alapú kiugró értékek kezelése
- Idősoros vizualizációk készítése (Seaborn, Bokeh)
- Térképes vizualizáció (Folium)

## Eredmények

A notebook vizuálisan szemlélteti a magyarországi és régiós benzinárak közötti különbségeket és azok időbeli változását.

## Licenc

Ez a projekt kizárólag oktatási célokat szolgál.
