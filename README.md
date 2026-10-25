### Maciej Bujalski

Analityk danych w PKO BP, Łódź. Na co dzień SQL Server, Python i Power BI: raporty sprzedażowe,
nocne ładowanie danych z hurtowni i aplikacje dla zespołów sprzedaży. Po godzinach buduję projekty,
w których przechodzę całą drogę od surowego API do modelu, który codziennie sam liczy prognozę.

*Data analyst at a Polish bank (SQL, Python, Power BI), growing towards data engineering and ML.
Projects below are documented in Polish; code and commit history speak for themselves.*

**Projekty**

- [**prognoza-energii-pl**](https://github.com/bujalek12/prognoza-energii-pl): prognoza zapotrzebowania,
  wiatru i fotowoltaiki w polskim systemie energetycznym na dobę naprzód. Pipeline z API PSE
  i Open-Meteo, hurtownia w dbt na DuckDB, LightGBM z backtestem i przedziałami niepewności,
  codzienne uruchomienie w GitHub Actions i porównanie z oficjalnym planem PSE.
  Działająca aplikacja: [bilans-kse.streamlit.app](https://bilans-kse.streamlit.app/?motyw=ciemny)
- [**paczkomaty-pl**](https://github.com/bujalek12/paczkomaty-pl): ilu Polaków ma paczkomat w 500 m
  i gdzie postawić kolejne. Siatka H3, ludność skalibrowana do GUS, hurtownia dbt z testami jakości,
  model zapotrzebowania (LightGBM, walidacja przestrzenna) i optymalizacja lokalizacji sprawdzona
  na paczkomatach, które są właśnie w budowie. Codzienny zrzut sieci w GitHub Actions.
  Działająca aplikacja: [zasieg-paczkomatow.streamlit.app](https://zasieg-paczkomatow.streamlit.app)
- [**predykcja-chorob-serca**](https://github.com/bujalek12/predykcja-chorob-serca): praca inżynierska.
  9 modeli ML i 7 technik równoważenia klas na danych CDC BRFSS z trzech lat (AUC do 0,87).

**Narzędzia:** Python (pandas, scikit-learn, LightGBM, H3), SQL (SQL Server, DuckDB), dbt, Power BI / DAX,
Streamlit, Git, GitHub Actions, R
