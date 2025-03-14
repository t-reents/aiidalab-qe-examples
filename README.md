# aiidalab-qe-examples
Collection of examples ready to be imported in the Quantum ESPRESSO app.

## How to add new examples
To add a new example, please put the corresping export file in the `examples` folder, and add a line in the `examples_list.txt` file in the corresponding format: `<name_of_the_file> - <short description or label of the QeAppWorkChain node>`.  

### How to add a plugin dependency

If the example requires a given set of Quantum ESPRESSO app plugins to be loaded, you can specific them in the corresponding line of the `examples_list.txt`, just adding: `/ plugins: <plugin1>, <plugin2>` and so on. You can check the already provided examples.

## Versioning
This repo will be tagged to mark its compatability with versions of the Quantum ESPRESSO app.
