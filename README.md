# Train-FLAN-T5-Model-from-Scratch-for-Question-Answering-Task-for-a-given-text-input

__Content in the jupyter notebook__
1. Use a pre-trained google/flan-t5-small as the model.
2. Verify if the summarization task works.
3. Verify if the Q&A task works.
4. Verify if English to French translation task works.
5. Programmatically print the names of all the model layers and their dimensions.
6. Programmatically print the total number of parameters/weights in this model.
7. Set the tensor in final layer (decoder.final_layer_norm.weight) to all zeros.
8. Verify if the Q&A task works after resetting the weights of the above layer.
9. Replace the decoder.final_layer_norm.weight with a layer of smaller dimensions and adjust all the dependent layers to match the dimension
10. Reload the original google/flan-t5-small model.
11. Train the model for a Q&A task that takes a context as additional input along with the question. You can use SQuAD dataset (https://rajpurkar.github.io/SQuAD-explorer/ ) or the smaller Topioca dataset (https://mcgill-nlp.github.io/topiocqa/) . Choose an appropriate task prefix/trigger word and justify the choice.
12. Evaluate the quality of the model

