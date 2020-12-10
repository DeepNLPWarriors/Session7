# Session7

In this assignment we have trained sentiment analysis from stanford dataset

Here are techniques used

- Used pytreebank which is used for preprocessing the dataset
- Used glove embedding
- Used goooge translate for data augmentation
- Three data augmentation used are : backtranslation, random deletion, random swap
- Used two layer LSTM
- Used dropout


## Training Logs:

Epoch: 1
	Train Loss: 1.518 | Train Acc: 37.24%
	 Val. Loss: 1.479 |  Val. Acc: 42.31% 

	Epoch: 2
	Train Loss: 1.440 | Train Acc: 45.69%
	 Val. Loss: 1.477 |  Val. Acc: 40.79% 

	Epoch: 3
	Train Loss: 1.371 | Train Acc: 53.44%
	 Val. Loss: 1.473 |  Val. Acc: 41.50% 

	Epoch: 4
	Train Loss: 1.314 | Train Acc: 59.76%
	 Val. Loss: 1.477 |  Val. Acc: 41.69% 

	Epoch: 5
	Train Loss: 1.254 | Train Acc: 65.76%
	 Val. Loss: 1.473 |  Val. Acc: 41.82% 

	Epoch: 6
	Train Loss: 1.209 | Train Acc: 70.16%
	 Val. Loss: 1.488 |  Val. Acc: 39.73% 

	Epoch: 7
	Train Loss: 1.174 | Train Acc: 73.69%
	 Val. Loss: 1.489 |  Val. Acc: 39.95% 

	Epoch: 8
	Train Loss: 1.147 | Train Acc: 76.26%
	 Val. Loss: 1.503 |  Val. Acc: 38.96% 

	Epoch: 9
	Train Loss: 1.124 | Train Acc: 78.46%
	 Val. Loss: 1.500 |  Val. Acc: 38.69% 

	Epoch: 10
	Train Loss: 1.107 | Train Acc: 80.21%
	 Val. Loss: 1.503 |  Val. Acc: 39.14% 

	Epoch: 11
	Train Loss: 1.092 | Train Acc: 81.57%
	 Val. Loss: 1.499 |  Val. Acc: 39.18% 

	Epoch: 12
	Train Loss: 1.082 | Train Acc: 82.52%
	 Val. Loss: 1.500 |  Val. Acc: 39.05% 

	Epoch: 13
	Train Loss: 1.073 | Train Acc: 83.49%
	 Val. Loss: 1.501 |  Val. Acc: 39.18% 

	Epoch: 14
	Train Loss: 1.062 | Train Acc: 84.49%
	 Val. Loss: 1.513 |  Val. Acc: 37.80% 

	Epoch: 15
	Train Loss: 1.056 | Train Acc: 85.11%
	 Val. Loss: 1.508 |  Val. Acc: 38.56% 

	Epoch: 16
	Train Loss: 1.051 | Train Acc: 85.64%
	 Val. Loss: 1.503 |  Val. Acc: 39.59% 

	Epoch: 17
	Train Loss: 1.043 | Train Acc: 86.34%
	 Val. Loss: 1.507 |  Val. Acc: 38.29% 

	Epoch: 18
	Train Loss: 1.040 | Train Acc: 86.63%
	 Val. Loss: 1.524 |  Val. Acc: 37.35% 

	Epoch: 19
	Train Loss: 1.034 | Train Acc: 87.25%
	 Val. Loss: 1.508 |  Val. Acc: 38.29% 

	Epoch: 20
	Train Loss: 1.031 | Train Acc: 87.45%
	 Val. Loss: 1.523 |  Val. Acc: 37.04% 

	Epoch: 21
	Train Loss: 1.025 | Train Acc: 88.07%
	 Val. Loss: 1.505 |  Val. Acc: 39.09% 

	Epoch: 22
	Train Loss: 1.021 | Train Acc: 88.51%
	 Val. Loss: 1.513 |  Val. Acc: 38.51% 

	Epoch: 23
	Train Loss: 1.019 | Train Acc: 88.66%
	 Val. Loss: 1.519 |  Val. Acc: 37.75% 

	Epoch: 24
	Train Loss: 1.015 | Train Acc: 89.08%
	 Val. Loss: 1.515 |  Val. Acc: 38.06% 

	Epoch: 25
	Train Loss: 1.013 | Train Acc: 89.24%
	 Val. Loss: 1.522 |  Val. Acc: 37.75% 

Best Validation Accuracy: 0.4230769234044211
