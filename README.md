# EMFSyncer Solution to the TTC2020 Round-trip Case

* The EMFSyncer solution can be found at [ttc2020.emfsyncer](ttc2020.emfsyncer/).
* The original benchmark framework available [here](https://github.com/lbeurerkellner/ttc2020) has been modified. Please use this [de.hub.mse.ttc2020.benchmark](de.hub.mse.ttc2020.benchmark/). 
* The modified reference solution can be found at [de.hub.mse.ttc2020.solution](de.hub.mse.ttc2020.solution/).


## Installation guidelines

* Download [Eclipse IDE for Java and DSL Developers](https://www.eclipse.org/downloads/packages/)
* Install EMF Compare 3.3 from the update site `https://download.eclipse.org/modeling/emf/compare/updates/releases/3.3/` and restart Eclipse. 
* Install AJDT for Eclipse 4.10, from the update site `http://download.eclipse.org/tools/ajdt/410/dev/update` and restart Eclipse.

## Get the EMFSyncer solution and run it

* Clone the git repository containing the EMFSyncer solution: `https://github.com/emf-syncer/ttc20-roundtrip.git` using EGit
* From the EGit repository view, select the three projects and click `Import projects`, then select `Import existing Eclipse projects (3 selected)` and click `Finished`.
* Go to the Java perspective, select the project `ttc2020.emfsyncer`. Then click on `Project > Clean...`.
* Task solutions can be found [here](./ttc2020.emfsyncer/src/emfsyncer/solution/)
* To run functional tests use [this launch configuration](./ttc2020.emfsyncer/AllJavaFunctionalTests.launch) (right click > `Run As` > `AllJavaFunctionalTests`)
* To run performance tests use [this launch configuration](./ttc2020.emfsyncer/AllJavaPerformanceTests.launch) (right click > `Run As` > `AllJavaPerformanceTests`)
 