# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures

Includes outright monthly contracts plus calendar spreads The schema gives one bar per contract per trading day.


## DataFrame Glimpse

```
Rows: 11764
Columns: 7
$ date   <datetime[ns]> 2026-10-13 00:00:00
$ symbol          <str> 'ZQ:BF J7-K7-N7'
$ open            <f64> -2.0
$ high            <f64> -2.0
$ low             <f64> -2.0
$ close           <f64> -2.0
$ volume          <u64> 13


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com                                   |
| Tags                           | Ff, Futures, Zq                                             |
| Access Types                   |                                       |
| How is data pulled?            | API pull with Databento subscription                                                   |
| Data available up to (min)     | None                                                             |
| Data available up to (max)     | None                                                             |
| Dataframe Path                 | /home/eutley/Documents/Class/Pipelines/hw2-eutley27/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///home/eutley/Documents/Class/Pipelines/hw2-eutley27/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-14 20:36:56           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

