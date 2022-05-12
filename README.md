# CSE543_Final_Project_TKT
## Introduction
This project focuses on implementing a Transformer for Knowledge Tracing (KT) problems on the basis of the SAINT model (https://github.com/Shivanandmn/Knowledge-Tracing-SAINT). We adapted the input embedding and the model, and then tested the model on the ASSISTments2017 dataset. Compared to other transformer models' performance on ASSISTments2017 (AUC=0.7181), our model can increase the AUC by 2% (AUC=0.7301).

## Dataset
[ASSISTment2017] (https://drive.google.com/drive/folders/1aCg5ln4mBeT1VWDBRq7XG4gBb46S4pra?usp=sharing)

[Riiid] (https://drive.google.com/drive/folders/17YgOwy0X3-EIAZJw9DgXKG0pYJrVgz95?usp=sharing)

## Usage
[TKT.ipynb] (./main/CSE543_Final_Project_TKT/TKT.ipynb)

Predict KT problem using transformer. Recommended running environment: Google Colab.

[DKT.ipynb] (./main/CSE543_Final_Project_TKT/DKT.ipynb)

Predict KT problem using LSTM. Recommended running environment: Jupyter Notebook.

## References
[1] Piech, C., Bassen, J., Huang, J., Ganguli, S., Sahami, M., Guibas, L. J., & Sohl-Dickstein, J. (2015). Deep knowledge tracing. Advances in neural information processing systems, 28.

[2] Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. Advances in neural information processing systems, 30.

[3] Pu, S., Yudelson, M., Ou, L., & Huang, Y. (2020, July). Deep knowledge tracing with transformers. In International Conference on Artificial Intelligence in Education (pp. 252-256). Springer, Cham.

[4] Choi, Y., Lee, Y., Cho, J., Baek, J., Kim, B., Cha, Y., ... & Heo, J. (2020, August). Towards an appropriate query, key, and value computation for knowledge tracing. In Proceedings of the Seventh ACM Conference on Learning@ Scale (pp. 341-344).

[5] Janizek, J. D., Sturmfels, P., & Lee, S. I. (2021). Explaining explanations: Axiomatic feature interactions for deep networks. Journal of Machine Learning Research, 22(104), 1-54.

[6] Choi, Y., Lee, Y., Shin, D., Cho, J., Park, S., Lee, S., ... & Heo, J. (2020, July). Ednet: A large-scale hierarchical dataset in education. In International Conference on Artificial Intelligence in Education (pp. 69-73). Springer, Cham.

[7] Xiao, Z., Li, Z., and Pardos, Z. (2018). AutoQuiz: A Personalized, Adaptive, Test Practice System (Abstract Only). In Proceedings of the 49th ACM Technical Symposium on Computer Science Education (SIGCSE '18). Association for Computing Machinery, New York, NY, USA, 1089. https://doi.org/10.1145/3159450.3162317

[8] Piech, C., Bassen, J., Huang, J., Ganguli, S., Sahami, M., Guibas, L. J., & Sohl-Dickstein, J. (2015). Deep knowledge tracing. Advances in neural information processing systems, 28.
