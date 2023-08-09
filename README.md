# Bike Sharing Assignment

> Build a model for the prediction of bike rental daily count based on the environmental and seasonal settings

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same.

- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

- You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- found the equation to be cnt = 0.1956 x const + 0.2344 x yr + 0.4795 x temp - 0.1498 x windspeed - 0.0572 x season_spring + 0.0623 x season_summer + 0.0937 x season_winter + 0.0854 x mnth_sep - 0.0461 x weekday_sun - 0.2856 x weathersit_light_snowrain - 0.0790 x weathersit_Misty
- Demand for bikes depend on yr, temp , windspeed , season_spring, season_summer, season_winter, mnth_sep ,weekday_sun,weathersit_Light_snowrain and weathersit_Misty
- Spring season when there is no rain or snow is the best time for higher sales
- Sales is increasing every year

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- scikit-learn-intelex: 20230228.214818
- diff-match-patch: 20200713
- daal4py: 2023.0.2
- certifi: 2022.12.7
- fsspec: 2022.11.0
- xarray: 2022.11.0
- regex: 2022.7.9
- dask: 2022.7.0
- distributed: 2022.7.0
- pytz: 2022.7
- imagecodecs: 2021.8.26
- tifffile: 2021.7.2
- pywin32: 305.1
- setuptools: 65.6.3
- cryptography: 39.0.1
- keyring: 23.4.0
- conda: 23.3.1
- pyzmq: 23.2.0
- boltons: 23.0.0
- pyopenssl: 23.0.0
- black: 22.6.0
- pip: 22.3.1
- twisted: 22.2.0
- attrs: 22.1.0
- packaging: 22.0
- argon2-cffi: 21.3.0
- incremental: 21.3.0
- argon2-cffi-bindings: 21.2.0
- hyperlink: 21.0.0
- automat: 20.2.0
- service-identity: 18.1.0
- constantly: 15.1.0
- pyqt5-sip: 12.11.0
- pillow: 9.4.0
- ipython: 8.10.0
- click: 8.0.4
- tenacity: 8.0.1
- pycurl: 7.45.1
- ipywidgets: 7.6.5
- jupyter-client: 7.3.4
- pytest: 7.1.2
- ipykernel: 6.19.2
- jupyter-console: 6.6.2
- sip: 6.6.2
- nbconvert: 6.5.4
- notebook: 6.5.2
- pydocstyle: 6.3.0
- tornado: 6.1
- flake8: 6.0.0
- pyyaml: 6.0
- pyqt5: 5.15.7
- pyqtwebengine: 5.15.4
- isort: 5.9.3
- plotly: 5.9.0
- psutil: 5.9.0
- traitlets: 5.7.1
- nbformat: 5.7.0
- spyder: 5.4.1
- qtconsole: 5.4.0
- ujson: 5.4.0
- zope.interface: 5.4.0
- smart-open: 5.2.1
- jupyter-core: 5.2.0
- decorator: 5.1.1
- astropy: 5.1
- python-slugify: 5.0.2
- sphinx: 5.0.2
- tqdm: 4.64.1
- fonttools: 4.25.0
- transformers: 4.24.0
- jsonschema: 4.17.3
- importlib-metadata: 4.11.3
- beautifulsoup4: 4.11.1
- lxml: 4.9.1
- pexpect: 4.8.0
- typing-extensions: 4.4.0
- gensim: 4.3.0
- textdistance: 4.2.1
- bleach: 4.1.0
- pyodbc: 4.0.34
- mock: 4.0.3
- chardet: 4.0.0
- conda-build: 3.24.0
- ply: 3.11
- zipp: 3.11.0
- filelock: 3.9.0
- tables: 3.7.0
- h5py: 3.7.0
- matplotlib: 3.7.0
- nltk: 3.7
- flit-core: 3.6.0
- jupyterlab: 3.5.3
- widgetsnbextension: 3.5.2
- anyio: 3.5.0
- conda-verify: 3.4.2
- markdown: 3.4.1
- idna: 3.4
- bcrypt: 3.2.0
- tldextract: 3.2.0
- lz4: 3.1.3
- jinja2: 3.1.2
- intervaltree: 3.1.0
- prompt-toolkit: 3.0.36
- openpyxl: 3.0.10
- pyparsing: 3.0.9
- qdarkstyle: 3.0.2
- colorcet: 3.0.1
- pyflakes: 3.0.1
- requests: 2.28.1
- imageio: 2.26.0
- pycparser: 2.21
- jupyterlab-server: 2.19.0
- fastjsonschema: 2.16.2
- pylint: 2.16.2
- astroid: 2.14.2
- pygments: 2.11.2
- babel: 2.11.0
- pycodestyle: 2.10.0
- libarchive-c: 2.9
- networkx: 2.8.4
- numexpr: 2.8.4
- python-dateutil: 2.8.2
- paramiko: 2.8.1
- scrapy: 2.8.0
- platformdirs: 2.5.2
- bokeh: 2.4.3
- spyder-kernels: 2.4.1
- anaconda-navigator: 2.4.0
- mkl-service: 2.4.0
- pyjwt: 2.4.0
- sortedcontainers: 2.4.0
- soupsieve: 2.3.2.post1
- pylint-venv: 2.3.0
- flask: 2.2.2
- werkzeug: 2.2.2
- qtpy: 2.2.0
- snowballstemmer: 2.2.0
- threadpoolctl: 2.2.0
- watchdog: 2.1.6
- markupsafe: 2.1.1
- jsonpointer: 2.1
- zict: 2.1.0
- pywinpty: 2.0.10
- pydispatcher: 2.0.5
- asttokens: 2.0.5
- charset-normalizer: 2.0.4
- conda-package-handling: 2.0.2
- pyhamcrest: 2.0.2
- pyviz-comms: 2.0.2
- greenlet: 2.0.1
- itsdangerous: 2.0.1
- tomli: 2.0.1
- cloudpickle: 2.0.0
- pyerfa: 2.0.0
- sphinxcontrib-htmlhelp: 2.0.0
- jsonpatch: 1.32
- urllib3: 1.26.14
- numpy: 1.23.5
- jupyter-server: 1.23.4
- w3lib: 1.21.0
- six: 1.16.0
- holoviews: 1.15.4
- cffi: 1.15.1
- wrapt: 1.14.1
- param: 1.12.3
- torch: 1.12.1
- anaconda-client: 1.11.2
- sympy: 1.11.1
- py: 1.11.0
- scipy: 1.10.0
- pkginfo: 1.9.6
- send2trash: 1.8.0
- cookiecutter: 1.7.3
- pep8: 1.7.1
- pysocks: 1.7.1
- python-lsp-server: 1.7.1
- rope: 1.7.0
- tblib: 1.7.0
- backports.functools-lru-cache: 1.6.4
- autopep8: 1.6.0
- lazy-object-proxy: 1.6.0
- parsel: 1.6.0
- nest-asyncio: 1.5.6
- pandas: 1.5.3
- debugpy: 1.5.1
- requests-file: 1.5.1
- queuelib: 1.5.0
- numpydoc: 1.5.0
- pandocfilters: 1.5.0
- pynacl: 1.5.0
- sqlalchemy: 1.4.39
- menuinst: 1.4.19
- appdirs: 1.4.4
- kiwisolver: 1.4.4
- imagesize: 1.4.1
- pywavelets: 1.4.1
- atomicwrites: 1.4.0
- pooch: 1.4.0
- bottleneck: 1.3.5
- mkl-fft: 1.3.1
- text-unidecode: 1.3
- pytoolconfig: 1.2.5
- arrow: 1.2.3
- clyent: 1.2.2
- mkl-random: 1.2.2
- qtawesome: 1.2.2
- mpmath: 1.2.1
- python-lsp-black: 1.2.1
- scikit-learn: 1.2.1
- tinycss2: 1.2.1
- partd: 1.2.0
- sniffio: 1.2.0
- unidecode: 1.2.0
- sphinxcontrib-serializinghtml: 1.1.5
- munkres: 1.1.4
- iniconfig: 1.1.1
- joblib: 1.1.1
- cssselect: 1.1.0
- et-xmlfile: 1.1.0
- win-inet-pton: 1.1.0
- conda-repo-cli: 1.0.41
- contourpy: 1.0.5
- itemloaders: 1.0.4
- msgpack: 1.0.3
- sphinxcontrib-qthelp: 1.0.3
- sphinxcontrib-applehelp: 1.0.2
- sphinxcontrib-devhelp: 1.0.2
- twisted-iocpsupport: 1.0.2
- whatthepatch: 1.0.2
- heapdict: 1.0.1
- pathlib: 1.0.1
- rtree: 1.0.1
- sphinxcontrib-jsmath: 1.0.1
- backports.weakref: 1.0.post1
- python-lsp-jsonrpc: 1.0.0
- backports.tempfile: 1.0
- jupyter: 1.0.0
- jupyterlab-widgets: 1.0.0
- locket: 1.0.0
- pluggy: 1.0.0
- websocket-client: 0.58.0
- numba: 0.56.4
- llvmlite: 0.39.1
- wheel: 0.38.4
- yapf: 0.31.0
- xlwings: 0.29.1
- scikit-image: 0.19.3
- zstandard: 0.19.0
- future: 0.18.3
- docutils: 0.18.1
- jedi: 0.18.1
- pyrsistent: 0.18.0
- ruamel.yaml: 0.17.21
- ruamel-yaml-conda: 0.17.21
- terminado: 0.17.1
- datashader: 0.14.4
- panel: 0.14.3
- prometheus-client: 0.14.1
- statsmodels: 0.13.5
- seaborn: 0.12.2
- cytoolz: 0.12.0
- toolz: 0.12.0
- tokenizers: 0.11.4
- anaconda-project: 0.11.1
- tomlkit: 0.11.1
- cycler: 0.11.0
- docstring-to-markdown: 0.11
- pathspec: 0.10.3
- toml: 0.10.2
- huggingface-hub: 0.10.1
- imbalanced-learn: 0.10.1
- jmespath: 0.10.0
- json5: 0.9.6
- requests-toolbelt: 0.9.1
- jellyfish: 0.9.0
- tabulate: 0.8.10
- mistune: 0.8.4
- executing: 0.8.3
- parso: 0.8.3
- hvplot: 0.8.2
- alabaster: 0.7.12
- pickleshare: 0.7.5
- defusedxml: 0.7.1
- brotlipy: 0.7.0
- conda-package-streaming: 0.7.0
- glob2: 0.7
- mccabe: 0.7.0
- ptyprocess: 0.7.0
- intake: 0.6.7
- pycosat: 0.6.4
- python-snappy: 0.6.1
- conda-pack: 0.6.0
- multipledispatch: 0.6.0
- nbclient: 0.5.13
- datashape: 0.5.4
- patsy: 0.5.3
- nbclassic: 0.5.2
- inflection: 0.5.1
- webencodings: 0.5.1
- poyo: 0.5.0
- pyct: 0.5.0
- pyasn1: 0.4.8
- colorama: 0.4.6
- binaryornot: 0.4.4
- mypy-extensions: 0.4.3
- pyls-spyder: 0.4.0
- conda-token: 0.4.0
- entrypoints: 0.4
- dill: 0.3.6
- navigator-updater: 0.3.0
- itemadapter: 0.3.0
- pyasn1-modules: 0.2.8
- ruamel.yaml.clib: 0.2.6
- wcwidth: 0.2.5
- notebook-shim: 0.2.2
- pure-eval: 0.2.2
- qstylizer: 0.2.2
- tbb: 0.2
- wincertstore: 0.2
- backcall: 0.2.0
- ipython-genutils: 0.2.0
- jinja2-time: 0.2.0
- pywin32-ctypes: 0.2.0
- stack-data: 0.2.0
- protego: 0.1.16
- matplotlib-inline: 0.1.6
- conda-content-trust: 0.1.3
- comm: 0.1.2
- jupyterlab-pygments: 0.1.2
- three-merge: 0.1.1
-

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

Give credit here.

- This project was inspired by Upgrad COurse
- This project was based on Bike Sharing Assignment as part of PG course in AI and ML

## Contact

Created by [@Zelphire] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
