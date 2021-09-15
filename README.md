# Python-DiamondIndicatorMineral

These coding companions are designed to take you through the creation of neural networks to classify associated diamond contents for 5 different diamond indicator silicate minerals: G10 garnet (G10), eclogitic garnet (EG), chrome diopside (CRD), olivine (OL) and orthopyroxene (OPX). The csv data files are also available.

Diamond indicators are minerals that assist explorers in locating areas with diamonds. They were first recognized shortly after the discovery of the first diamond kimberlite pipes in the 1870s. By the 1970s, with the use of a scanning electron microscope (SEM), researchers were classifying these minerals using binary, or X-Y, diagrams to assist explorers with determining the likelihood of finding diamonds, but the classification did not distinguish between the diamond indicators associated with high and low diamond contents. This brings us to machine learning and neural networks. Using data collected from Benz (2006), neural networks were created to assist in the classification of diamond indicator silicate minerals associated with high or low diamond contents. The models created would greatly benefit from more samples from a greater variety of areas and future research would include testing the chemical complexity of SEM data for the ability to create reliable neural network models that could be used to assist exploration planning.

Please note that these scripts use Python-packages that are protected under their own licenses and it's recommended that each license is reviewed prior to use.

Package Descriptions

Package 'graphiz'; Ellson, J., Gansner, E., Hu, Y., North, S., Jacobsson, M., Fernandez, M., Hansen, M., Alexiev, V., Bilgin, A., Caldwell, D., Daniel, R.G., Dobkin, D., Dwyer, T., Janssen, E., Kelman, T., Foren, Y., Koutsofios, E., Lilly, B., Low., G. and Woodhull, G. (2021): https://graphviz.org/download/source/

Package 'keras'; Gulli, A. & Pal, S.(2021): https://keras.io/

Package 'matplotlib'; Silvestor, S., Valeriani, D., McDougall, D., Stansby, D., Firing, E., Prestat, E., Ariza, E., Perez, F., Thomas, I., Ernest, E., Ivanov, P., Nielsen, J.H., Seppänen, J.K., Kniazev, N., Rnou, M., Droettboom, M., Fitzpatrick, M., Rakitin, M., Varoquaux, N., Pal, N., E, P., Ganssle, P., Hobson, P., Sales de Andrade, E., Rougier, N.P., Sauerburger, F., Hannah, Corlay, S., Caswell, T.A., Hoffmann, T., Root, B. and Zalbalza, V. (2021): https://github.com/matplotlib

Package 'numpy'; Harris, C. R., Millman, K. J., van der Walt, S. J., Gommers, R., Virtanen, P., Cournapeau, D., … Oliphant, T. E. (2021): https://numpy.org/install/

Package 'pandas'; The pandas development team (2021): https://zenodo.org/record/5501881

Package 'plotly'; Krutchen, N., Postlethwaithe, B., Parmer, C., Bronson, C., Douglas, C., Benhmani,H., Mease, J.,  Schneider, K., Pace, A.,  Drezner, N. and Phan, K. (2021): https://github.com/plotly/

Package 'pydot'; Carrerra, E., Kalinowski, S. and Nowee, P.(2021): https://github.com/pydot/pydot

Package 'sklearn'; Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J., Passos, A., Cournapeau, D., Brucher, M., Perrot, M. and Duchesnay, E. (2021): https://scikit-learn.org/stable/install.html

Package 'seaborn'; Waskom, M.L. (2021): https://seaborn.pydata.org/index.html

Package 'tensorflow'; Abadi, M., Agarwal, A., Barham, P., Brevdo, E., Chen, Z., Citro, C., Corrado, G., Davis, A., Dean, J., Devin, M., Ghemawat, S., Goodfellow, I., Harp, A., Irving, G., Isard, M., Jozefowicz, R., Jia, Y., Kaiser, L., Kudlur, M., Levenberg, J., Mané, D., Schuster, M., Monga, R., Moore, S., Murray, D., Olah, C., Shlens, J., Steiner, B., Sutskever, I., Talwar, K., Tucker, P., Vanhoucke, V., Vasudevan, V., Viégas, F., Vinyals, O., Warden, P., Wattenberg, M., Wicke, M., Yu, Y., and Zheng, X. (2021): https://tensorflow.org

Script 'feature-importance-neural-networks'; Rebelo de Sá, C. (2021): https://github.com/rebelosa/feature-importance-neural-networks

References

Abadi, M., Agarwal, A., Barham, P., Brevdo, E., Chen, Z., Citro, C., Corrado, G., Davis, A., Dean, J., Devin, M., Ghemawat, S., Goodfellow, I., Harp, A., Irving, G., Isard, M., Jozefowicz, R., Jia, Y., Kaiser, L., Kudlur, M., Levenberg, J., Mané, D., Schuster, M., Monga, R., Moore, S., Murray, D., Olah, C., Shlens, J., Steiner, B., Sutskever, I., Talwar, K., Tucker, P., Vanhoucke, V., Vasudevan, V., Viégas, F., Vinyals, O., Warden, P., Wattenberg, M., Wicke, M., Yu, Y., and Zheng, X. (2015).
TensorFlow: Large-scale machine learning on heterogeneous systems: https://tensorflow.org

Benz, Diana M., "Diamond indicators, trace elements, and kimberlites: A comparative study using
examples from the Slave and Kaapvaal cratons." (2006). Electronic Theses and Dissertations. 7126.
https://scholar.uwindsor.ca/etd/7126 

Benz, D. (2021). Python-DiamondIndicatorMineral. 1.0. Script 'CodingCompanion_DiamondIndicatorSilicateMinerals-NeuralNetwork-CRD-clr'. Jupyter Notebook script version 6.3.0.

Benz, D. (2021). Python-DiamondIndicatorMineral. 1.0. Script 'CodingCompanion_DiamondIndicatorSilicateMinerals-NeuralNetwork-EG-clr'. Jupyter Notebook script version 6.3.0.

Benz, D. (2021). Python-DiamondIndicatorMineral. 1.0. Script 'CodingCompanion_DiamondIndicatorSilicateMinerals-NeuralNetwork-G10-clr'. Jupyter Notebook script version 6.3.0.

Benz, D. (2021). Python-DiamondIndicatorMineral. 1.0. Script 'CodingCompanion_DiamondIndicatorSilicateMinerals-NeuralNetwork-OL-clr'. Jupyter Notebook script version 6.3.0.

Benz, D. (2021). Python-DiamondIndicatorMineral. 1.0. Script 'CodingCompanion_DiamondIndicatorSilicateMinerals-NeuralNetwork-OPX-clr'. Jupyter Notebook script version 6.3.0.

Carrerra, E. (2004). Pydot: https://pydotplus.readthedocs.io/

Ellson, J., Gansner, E., Koutsofios, L., North, S., Woodhull, G. (2001). Graphiz - open source graph drawing tools. Lecture Notes in Computer Science. Springer-Verlag, 483-484. https://graphviz.org/.

Gulli, A. & Pal, S., (2017). Deep learning with Keras, Packt Publishing Ltd. https://keras.io/

Harris, C. R., Millman, K. J., van der Walt, S. J., Gommers, R., Virtanen, P., Cournapeau, D., … Oliphant, T. E. (2020). Array programming with NumPy. Nature, 585, 357–362. https://doi.org/10.1038/s41586-020-2649-2

Hunter, J.D. (2007). Matplotlib: A 2 D graphics environment. Computing in Science & Engineering, 9(3), 90-95. https://ieeexplore.ieee.org/document/4160265

McKinney, W. (2010). Data Structures for Statistical Computing in Python. Proceedings of the 9th Python in Science Conference, 56-61: http://conference.scipy.org/proceedings/scipy2010/mckinney.html.

Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J., Passos, A., Cournapeau, D., Brucher, M., Perrot, M. and Duchesnay, E. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 285-2830. https://www.jmlr.org/papers/volume12/pedregosa11a/pedregosa11a.pdf

Plotly Technologies Inc. (2015). Collaborative Data Science. Plotly Technologies Inc., Montréal, QC. https://plot.ly

Rebelo de Sá, C. (2019). Variance-based feature importance in neural networks. 22st International Conference on Discovery Science (DS 2019) Split, Croatia, October 28-30, 2019. https://link.springer.com/chapter/10.1007/978-3-030-33778-0_24

Waskom, M.L. (2021). seaborn: statistical data visualization. Journal of Open Source Software, 6 (60), 3021. https://joss.theoj.org/papers/10.21105/joss.03021 
