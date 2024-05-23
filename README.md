<!-- Crear un entorn virtual:  -->


    python -m venv .venv

    source .venv/bin/activate

<!-- Instalem el requirements.txt si no el tenim  -->

    pip install -r requirements.txt


<!-- Iniciem l'aplicació amb aquesta opció -->

    flask run --debug



<!-- Mode remot -->

*En el mode remot, l'aplicació llegeix l'XML directament de la web de La Vanguardia. Per utilitzar aquest mode, assegura't que el paràmetre mode a config.py estigui configurat com a remote.*

Aqui el codi:

    # config.py
    MODE = 'remote'






<!-- Recursos addiocionals o links -->

Aqui teniu el link a una guia sobre els entorns virtuals en python:

    https://docs.python.org/es/3/tutorial/venv.html