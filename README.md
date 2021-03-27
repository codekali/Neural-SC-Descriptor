# Neural Souce Code Descriptor

This is a deep learning project to summarize java methods into one line summary using state-of-the-art T5-Transformers. 

## Dataset

The dataset for this task has been taken from the DeepCom GitHub repository.

Repository: [EMSE-DeepCom](https://github.com/xing-hu/EMSE-DeepCom)

Dataset: [Gdrive link(select RQ3)](https://drive.google.com/drive/folders/130liaynevaYo2AhNoFtadtc7uBS12_aW?usp=sharing)


## Usage

Clone this repo using `git cli` by 
`git clone https://www.github.com/codekali/neural-sc-descriptor.git`

Extract the downloaded dataset and create a folder named `data` in the cloned repo. Create folders `train`, `val` and `test` inside the data folder. 

Move the `train.sbt` and `train.nl` files from the dataset extracted folder to the train folder. Do the same for `val` and `test` files too.

## Training

Open the folder in a `jupyter notebook` and run the `train.ipynb` file. 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
