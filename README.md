# IDL-Project-Team-54
This is the project code of gnn-based spotify playlist recommendation. 

The notebook is setup in kaggle environment, so please adjust your file allocation accordingly.

To run this notebook, you will need a GPU and access to Spotify Million Playlist Dataset, which is an open dataset online.

The environment setup might take a while, but you can directly run all the code up until "For example" part, where you'll have to define what specific model structures and other configs you would like.

There are several options, which involves LightGCN, GAT, postional embedding, alpha,number of layers. Besides, if you would like to explore the effect of number of heads, please navigate to class GCN for changing.

By selecting the parameter you're interested in, the model directly starts training, connects to wandb, and save training data in your designated directory. In one runtime, you can generate visualization directly by using functions in visualize part. However, if you lost connection with the notebook but managed to save training files or would like to revisit for comparison, it is still able to visualize the progress with pickle loading files. 

Further explanation and comments are included in the notebook. Thank you.
