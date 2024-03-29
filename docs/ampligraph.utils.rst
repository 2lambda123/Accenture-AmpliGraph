Utils
=====
.. currentmodule:: ampligraph.utils
.. automodule:: ampligraph.utils

This module contains utility functions for Knowledge Graph Embedding models.

Saving/Restoring Models
-----------------------

Models can be saved and restored from disk. This is useful to avoid re-training a model. On the contrary of what happens
for :meth:`~ampligraph.latent_features.models.ScoringBasedEmbeddingModel.save_weights` and
:meth:`~ampligraph.latent_features.models.ScoringBasedEmbeddingModel.save_weights`, the functions below allow to restart
the model training from where it was interrupted when the model was first saved.


.. autosummary::
    :toctree: generated
    :template: function.rst

    save_model
    restore_model


Visualization
-------------

Functions to visualize embeddings.

.. autosummary::
    :toctree: generated
    :template: function.rst

    create_tensorboard_visualizations

Others
-------------

Function various functions to be used at need.

.. autosummary::
    :toctree: generated
    :template: function.rst

    dataframe_to_triples
    preprocess_focusE_weights