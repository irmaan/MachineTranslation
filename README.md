## Deep Machine Translation

Machine translation, in its most basic definition, involves the process of converting written content from one language to another with the assistance of computer systems. The remarkable progress made in recurrent neural network (RNN) frameworks, including but not limited to Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU), has not only resulted in enhanced translation accuracy but has also significantly reduced the intricacies associated with traditional translation systems.

#### Dataset
- (http://www.manythings.org/anki/)
- y0u can download & add your desired source and definition languages



#### Usage

- python MachineTranslation.py --path './pes.txt' --epochs 20 --batch_size 32 --latent_dim 128 --num_samples 40000 --outdir '/your_desired_output_path/' --verbose 1 --mode train

- python MachineTranslation_word2vec.py --path './pes.txt' --epochs 20 --batch_size 32 --latent_dim 128 --num_samples 40000 --outdir '/hyour_desired_output_path/' --verbose 1 --mode train --embedding_dim 128














 






