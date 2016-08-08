# DO NOT EDIT, This Dockerfile is generated from ./tools/10_generate_Dockerfile.sh
FROM bjodah/bjodahimg16base:v1.1
MAINTAINER Björn Dahlgren <bjodah@DELETEMEgmail.com>
RUN \
    apt-get update && apt-get --quiet --assume-yes --no-install-recommends install     texlive-generic-recommended texlive-latex-recommended texlive-science texlive-fonts-recommended \
    texlive-fonts-extra texlive-latex-extra  texlive-lang-european lmodern latex-xcolor texlive-bibtex-extra biber \
    graphviz dot2tex dvipng \
    freeglut3-dev libglfw3-dev \
    expect-dev xutils-dev \
    phantomjs emscripten imagemagick \
    cython \
    python-wheel python3-wheel \
    python-matplotlib python3-matplotlib \
    python-mako python3-mako \
    python-mpmath python3-mpmath \
    python-scipy python3-scipy \
    python-pandas python3-pandas \
    python-astropy python3-astropy \
    python-rdkit librdkit1 rdkit-data \ 
    octave \
    libxrender1 fonts-dejavu pandoc \
    libgsl-dev libsundials-serial-dev coinor-libipopt-dev \
    libboost-all-dev libboost1.58-tools-dev && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
RUN \
    cd /tmp && \
    for FNAME in alabaster-0.7.9-py2.py3-none-any.whl apipkg-1.4-py2.py3-none-any.whl argh-0.26.2-py2.py3-none-any.whl ase-3.11.0.tar.gz astropy-1.2.1-cp27-cp27mu-manylinux1_x86_64.whl Babel-2.3.4-py2.py3-none-any.whl backports_abc-0.4-py2.py3-none-any.whl backports.shutil_get_terminal_size-1.0.0-py2.py3-none-any.whl blinker-1.4.tar.gz bokeh-0.12.1.tar.gz bottle-0.12.9.tar.gz cclib-1.4.tar.gz certifi-2016.8.2-py2.py3-none-any.whl CherryPy-7.1.0-py3-none-any.whl click-6.6.tar.gz cloudpickle-0.2.1-py2.py3-none-any.whl configparser-3.5.0.tar.gz coverage-4.2.tar.gz coveralls-1.1-py2.py3-none-any.whl cycler-0.10.0-py2.py3-none-any.whl decorator-4.0.10-py2.py3-none-any.whl docopt-0.6.2.tar.gz docutils-0.12-py3-none-any.whl docutils-0.12.tar.gz doit-0.29.0.tar.gz download.sh entrypoints-0.2.2-py2.py3-none-any.whl execnet-1.4.1-py2.py3-none-any.whl fastcache-1.0.2.tar.gz Flask-0.11.1-py2.py3-none-any.whl functools32-3.2.3-2.zip future-0.15.2.tar.gz futures-3.0.5-py2-none-any.whl ghp_import2-1.0.1-py2.py3-none-any.whl glfw-1.2.1.tar.gz gr-0.19.1.tar.gz grip-4.3.2.zip holoviews-1.6.1.tar.gz husl-4.0.3.tar.gz imagesize-0.7.1-py2.py3-none-any.whl ipykernel-4.3.1-py2.py3-none-any.whl ipython-5.0.0-py2.py3-none-any.whl ipython_genutils-0.1.0-py2.py3-none-any.whl ipywidgets-5.2.2-py2.py3-none-any.whl itsdangerous-0.24.tar.gz Jinja2-2.8-py2.py3-none-any.whl joblib-0.10.0-py2.py3-none-any.whl jsonschema-2.5.1-py2.py3-none-any.whl jupyter-1.0.0-py2.py3-none-any.whl jupyter_client-4.3.0-py2.py3-none-any.whl jupyter_console-5.0.0-py2.py3-none-any.whl jupyter_core-4.1.0-py2.py3-none-any.whl lancet-ioam-0.9.0.tar.gz Logbook-1.0.0.tar.gz lxml-3.6.1.tar.gz Mako-1.0.4.tar.gz Markdown-2.6.6.zip MarkupSafe-0.23.tar.gz matplotlib-1.5.1.tar.gz micawber-0.3.3.tar.gz mistune-0.7.3-py2.py3-none-any.whl mogli-0.2.3.tar.gz mpld3-0.2.tar.gz mpmath-0.19.tar.gz natsort-5.0.1-py2.py3-none-any.whl nbconvert-4.2.0-py2.py3-none-any.whl nbformat-4.0.1-py2.py3-none-any.whl Nikola-7.7.11-py2.py3-none-any.whl notebook-4.2.2-py2.py3-none-any.whl numpy-1.11.1-cp27-cp27mu-manylinux1_x86_64.whl numpydoc-0.6.0.tar.gz ordered-set-2.0.1.tar.gz param-1.4.1.zip path-and-address-2.0.1.zip pathlib2-2.1.0-py2.py3-none-any.whl pathtools-0.1.2.tar.gz patsy-0.4.1-py2.py3-none-any.whl pep8-1.7.0-py2.py3-none-any.whl periodictable-1.4.1.tar.gz pexpect-4.2.0-py2.py3-none-any.whl phpserialize-1.3.tar.gz pickleshare-0.7.3-py2.py3-none-any.whl piexif-1.0.4-py2.py3-none-any.whl Pillow-3.3.0-cp35-cp35m-manylinux1_x86_64.whl pip-8.1.2-py2.py3-none-any.whl prompt_toolkit-1.0.4-py2-none-any.whl prompt_toolkit-1.0.4-py3-none-any.whl ptyprocess-0.5.1-py2.py3-none-any.whl py-1.4.31-py2.py3-none-any.whl pycodeexport-0.1.0.tar.gz pycompilation-0.4.2.tar.gz pyflakes-1.2.3-py2.py3-none-any.whl pygal-2.2.3.tar.gz Pygments-2.1.3-py2.py3-none-any.whl pyinotify-0.9.6.tar.gz PyLaTeX-1.0.0.tar.gz PyOpenGL-3.1.0.tar.gz pyparsing-2.1.5-py2.py3-none-any.whl Pyphen-0.9.4-py2.py3-none-any.whl PyRSS2Gen-1.1.tar.gz pytest-2.9.2-py2.py3-none-any.whl pytest-cache-1.0.tar.gz pytest_cov-2.3.0-py2.py3-none-any.whl pytest-flakes-1.0.1.tar.gz pytest-pep8-1.0.6.tar.gz python3_packages.txt python_dateutil-2.5.3-py2.py3-none-any.whl python_packages.txt pytz-2016.6.1-py2.py3-none-any.whl PyYAML-3.11.zip pyzmq-15.3.0-cp27-cp27mu-manylinux1_x86_64.whl pyzmq-15.3.0-cp35-cp35m-manylinux1_x86_64.whl qtconsole-4.2.1-py2.py3-none-any.whl quantities-0.11.1.zip requests-2.10.0-py2.py3-none-any.whl setuptools-25.1.3-py2.py3-none-any.whl simplegeneric-0.8.1.zip singledispatch-3.4.0.3-py2.py3-none-any.whl six-1.10.0-py2.py3-none-any.whl smartypants-1.8.6-py2.py3-none-any.whl snowballstemmer-1.2.1-py2.py3-none-any.whl Sphinx-1.4.5-py2.py3-none-any.whl SQLAlchemy-1.0.14.tar.gz statsmodels-0.6.1.tar.gz stdeb-0.8.5.tar.gz sympy-1.0.tar.gz terminado-0.6.tar.gz toolz-0.8.0.tar.gz tornado-4.4.1.tar.gz traitlets-4.2.2-py2.py3-none-any.whl typogrify-2.0.7.tar.gz Unidecode-0.04.19.tar.gz virtualenv-15.0.2-py2.py3-none-any.whl watchdog-0.8.3.tar.gz wcwidth-0.1.7-py2.py3-none-any.whl webassets-0.11.1.tar.gz Werkzeug-0.11.10-py2.py3-none-any.whl widgetsnbextension-1.2.6-py2.py3-none-any.whl ws4py-0.3.5-py3-none-any.whl xarray-0.8.0-py2.py3-none-any.whl Yapsy-1.11.223.tar.gz ; do \
        wget --quiet http://hera.physchem.kth.se/~repo/bjodahimg16/v1.0/pypi/$FNAME -O /tmp/$FNAME; \
    done && \
    for PYPKG in ; do \
        python2 -m pip install --upgrade --no-index --find-links file:///tmp/ $PYPKG; \
        python3 -m pip install --upgrade --no-index --find-links file:///tmp/ $PYPKG; \
    done && \
    for PYPKG in future sympy pytest pytest-pep8 pytest-cov pytest-flakes sphinx periodictable pycompilation pycodeexport coveralls numpydoc jupyter argh quantities fastcache bottle sqlalchemy bokeh mogli pylatex joblib cclib toolz grip statsmodels mpld3 pip stdeb param holoviews[recommended] ase virtualenv xarray ; do \
        python2 -m pip install --no-index --find-links file:///tmp/ $PYPKG; \
        python3 -m pip install --no-index --find-links file:///tmp/ $PYPKG; \
    done && \
    for PYPKG in CherryPy Nikola[extras] ; do \
        python3 -m pip install --no-index --find-links file:///tmp/ $PYPKG; \
    done && \
    ln -s /usr/local/share/pyphen /usr/share/pyphen && \
    python -m IPython kernel install && \
    python3 -m IPython kernel install && \
    mkdir -p /root/.config/matplotlib/ && \
    echo "backend: Agg" > /root/.config/matplotlib/matplotlibrc && \
    sed -i 's/TkAgg/Agg/g' /etc/matplotlibrc && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
