# AXSIS-XES

This is a meta project that links all the repositories related to the axsis xes slow control system

| Purpose | Platform | Link |
|---------|----|------|
| Backend | Python 3.6+ | [axsis-xes](https://github.com/waltz-controls/axsis-xes)     |
| Middleware | Java 11+ | [magix](https://github.com/waltz-controls/magix-war-plugin) |
| Frontend | NodeJS 12+ | [axsis-gui](https://github.com/waltz-controls/axsis-xes-gui) |
| Tango Host   | Java 11+ | [virtual-host](https://github.com/waltz-controls/axsis-virtual-tango-host) |
| Tango Server | Java 11+ | [virtual-server](https://github.com/waltz-controls/axsis-tango-server) |
| Kubernetes | Microk8s | [axsis-kube](https://github.com/waltz-controls/axsis-kube) |

# Getting started for developers

To setup development environment one needs at least three projects: Backend, Middleware, Frontend

Here is how each of them can be set up for development:

## Backend

One will need PyCharm Professional and a Python environment (3.6+) installed on their system, however Conda is advised. Currently backend consists of two runnable:

`main.py` -- REST API. This is a Flask application and requires corresponding dependencies, run `pip install -r Requirements.txt` to install them. Configure PyCharm accordinly: [tutorial](https://www.jetbrains.com/help/pycharm/creating-flask-project.html)



`axsis.magix.py` -- Magix client



# Publications

[1] [Mazalova, V.; Khokhriakov, I.; Merkulova, O.; Nozik, A. A Novel Solution for Controlling Hardware Components of Accelerators and Beamlines. Preprints 2021, 2021080336 (doi: 10.20944/preprints202108.0336.v1).](https://www.preprints.org/manuscript/202108.0336/v1)
