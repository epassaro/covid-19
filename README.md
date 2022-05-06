# COVID-19 - Daily Update

![publish](https://github.com/epassaro/covid-19/workflows/publish/badge.svg)

> :warning: The site is no longer updated since 6/5/2022.

- ~Updates at 01:00 UTC (22:00 Argentina Standard Time).~
- Data downloaded from [John Hopkins University repository](https://github.com/CSSEGISandData/COVID-19).
- Data from Argentina provided by [Sistemas Mapache](https://github.com/SistemasMapache/Covid19arData). (Last updated: 9/11/2021).
## Automatic plots and site deploy

1. Fork the repo and clone it.
2. Go to 'Actions' and activate. 
3. Go to 'Settings' and choose to deploy GitHub pages in `gh-pages` branch.
4. New plots can be generated simply by adding new entries in `plots.yml`. You don't need to run the anything in your computer!.
5. Push your changes.
6. Wait until the action `publish` is ready and go to `https://<your-username>.github.io/covid-19`.

**Tip:** comment `[skip ci]` in the commit message to avoid building the site unnecesarily.

## Development

Requires a valid _Anaconda_ or _Miniconda_ installation.

```
$ conda env create -f environment.yml
$ conda activate covid-19
$ jupyter notebook daily_update.ipynb
```

## License

Code released under the [GNU GPLv3 License](https://raw.githubusercontent.com/epassaro/covid-19/master/LICENSE).
