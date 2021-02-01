install:
	conda install rdkit -c rdkit
	conda install opencv
	pip install -r requirements.txt

train-small:
	python train.py --data=configs/data_small.json --vocab=configs/vocab.json --training=configs/training.json --model=configs/model.json --output=results/small/

eval-small:
	python evaluate_txt.py --results=results/small/

