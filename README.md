# Image Processing for Computer Vision

Benvenuti nella repository del progetto di Image Processing for Computer Vision sviluppato dal gruppo composto da Angello Barletta, Giuseppe Buonomano, Daiana Cipollaro e Francesco Di Serio.

## Descrizione del Progetto

Il nostro progetto si concentra sull'Object Detection all'interno di immagini satellitari attraverso l'addestramento di reti neurali. Abbiamo suddiviso il lavoro in quattro parti principali:

1. **Pre-processing dei Dati (yolo-patches)**
   - Organizzazione del dataset per prepararlo all'addestramento delle reti.

2. **Addestramento del Modello YOLOv8 (training Yolo - prima parte)**
   - Utilizzo del framework YOLOv8 per l'addestramento di un modello di Object Detection.

3. **Addestramento del Modello FasterRCNN-ResNet50 (fasterrcnn-training)**
   - Implementazione dell'addestramento di un modello FasterRCNN-ResNet50 utilizzando PyTorch.

4. **Testing sui Dati Labellati e Non Labellati (training Yolo - seconda parte / fasterrcnn-testing)**
   - Valutazione delle performance dei modelli YOLOv8 e FasterRCNN-ResNet50 su immagini labellate e non labellate.
   - Calcolo delle metriche di valutazione.

## Struttura della Repository

- `yolo-patches.ipynb`: Contiene il file relativo alla fase di pre-processing dei dati.
- `training-yolo.ipynb`: Contiene il file relativo all'addestramento e al testing del modello YOLOv8.
- `coco-split-dataset.ipynb`: Contiene il file relativo allo splittaggio del dataset per il modello FasterRCNN-ResNet50.
- `fasterrcnn-training.ipynb`: Contiene il file relativo all'addestramento del modello FasterRCNN-ResNet50.
- `fasterrcnn-testing.ipynb`: Contiene il file di testing del modello FasterRCNN-ResNet50.

## Riferimenti Utilizzati

Abbiamo utilizzato diversi riferimenti per lo sviluppo del nostro progetto, tra cui:

- [xView Dataset](https://www.kaggle.com/datasets/hassanmojab/xview-dataset)
- [PyTorch Vision FasterRCNN](https://github.com/pytorch/vision/blob/main/torchvision/models/detection/faster_rcnn.py)
- [xView Dataset to YOLO and COCO Format](https://www.kaggle.com/code/ollypowell/xview-dataset-to-yolo-and-coco-format)
- [Ultralytics YOLOv5 Documentation](https://docs.ultralytics.com/datasets/detect/xview/#dataset-yaml)
- [Ultralytics YOLOv5 Training Examples](https://docs.ultralytics.com/modes/train/#usage-examples)
- [Article on Object Detection in Satellite Images](https://www.mdpi.com/2075-1702/11/7/677)

## Contributi

Siamo aperti a contributi e suggerimenti. Sentitevi liberi di aprire un'issue o una pull request.

Grazie per il vostro interesse nel nostro progetto!

