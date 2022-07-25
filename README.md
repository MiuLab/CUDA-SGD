# Controllable User Dialogue Act Augmentation for Dialogue State Tracking
- Paper link: 



## Installation

The package general requirements are

- Python >= 3.7
- Pytorch >= 1.5 (installation instructions [here](https://pytorch.org/))
- Transformers >= 3.0.2 (installation instructions [here](https://huggingface.co/transformers/))
 
The package can be installed by running the following command. Run

```sh setup.sh```

### Data

#### Multiwoz 2.1 & 2.2
It includes preprocessed MultiWOZ 2.1 and MultiWOZ 2.2 dataset. 
[Download](https://storage.cloud.google.com/sfr-coco-dst-research/multiwoz.zip), uncompress it, and place the 
resulting ```multiwoz``` folder under the root of the repository as ```./multiwoz```.
```
cd multiwoz
unzip multiwoz.zip
mv multiwoz/* ./
rmdir multiwoz
```

#### Multiwoz 2.3
If zip file not exist, downloads it from [Github](https://github.com/lexmen318/MultiWOZ-coref)
```
cd MultiWOZ-coref
unzip MultiWOZ2_3.zip
python ./split_data.py
```

### Details of CUDA: 
See ```./cuda/README.md```
### Details of CoCo: 
See ```./coco-dst/README.md```
### Details of TRADE: 
See ```./trade-dst/README.md```
### Details of SimpleTOD: 
See ```./simpletod/README.md```
### Details of TripPy: 
See ```./trippy-public/README.md```

## Citation
```
Pass
```

## License

This code includes other open source software components: 
[coco-dst](https://github.com/salesforce/coco-dst),
[trade-dst](https://github.com/jasonwu0731/trade-dst), 
[simpletod](https://github.com/salesforce/simpletod/), and 
[trippy-public](https://gitlab.cs.uni-duesseldorf.de/general/dsml/trippy-public).
Each of these software components have their own license. Please see them under 
```./coco-dst```, ```./trade-dst```, ```./simpletod```, and ```./trippy-public``` folders. 
