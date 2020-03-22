## Att-BiLSTM-CNN-for-knowledge-graph-completion in Keras


Keras implementation for the paper titled "Path-based reasoning approach for knowledge graph completion using CNN-BiLSTM with attention mechanism". Given a candidate relation and two entities, it encodes paths that connect the entities into a low-dimensional space using a convolutional operation followed by BiLSTM. An attention layer is also applied to capture the semantic correlation between a candidate relation and each path between two entities and attentively extract reasoning evidence from the representation of multiple paths to predict whether the entities should be connected by the candidate relation. 

For generating relation paths, we used https://github.com/noon99jaki/pra.

### If you use our code, please cite the paper



```Batselem Jagvaral, Wan-Kon Lee, Jae-Seung Roh, Min-Sung Kim, Young-Tack Park, <br/>Path-based reasoning approach for knowledge graph completion using <br/>CNN-BiLSTM with attention mechanism, <br/>Expert Systems With Applications (2019), <br/>doi: https://doi.org/10.1016/j.eswa.2019.112960```


### Acknowledgement

I'd like to thank my professor, Young-Tack Park for his support and advise.
