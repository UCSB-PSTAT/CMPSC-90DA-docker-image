# **CMPSC-90DA lab course**
## _Packages that the professor requested:_
 * Upgrade otter-grader=2.1.1 to 2.2.5 (completed)
***
### **Jupyter labextensions:**
``` Dockerfile
 jupyter contrib nbextension install --sys-prefix && \
    jupyter nbextension enable toc2/main --sys-prefix && \
    jupyter nbextension enable toggle_all_line_numbers/main --sys-prefix && \
    jupyter nbextension enable table_beautifier/main --sys-prefix && \
    \
    # Notebook extensions configurator (server on and interface off)
    jupyter nbextension install jupyter_nbextensions_configurator --py --sys-prefix && \
    jupyter nbextensions_configurator disable --sys-prefix && \
    jupyter serverextension enable jupyter_nbextensions_configurator --sys-prefix && \
```
 * jupyter serverextension enable --py nbgitpuller --sys-prefix
 


***
### **Pip Packages:**
``` Dockerfile
    pip install \ 
        nodejs \
        spacy \
        nltk \
        mplcursors \
        pytest \
        tweepy \
        PTable \
        pytest-custom-report \
        otter-grader==2.2.5 \
        datascience \
        jupyterlab 
```
 * vdiff
 * nbgitpuller
 ***
 ### **Conda Packages:**
 ``` Dockerfile
 npm install -g npm@latest codemirror
 ```


