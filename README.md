# Tensorflow_Images
Classiffication of Images

🌍 Street Food Image Classification with TensorFlow

A deep learning project that classifies street food images from around the world using TensorFlow/Keras. Ideal for exploring CNNs, transfer learning, and image augmentation.
📁 Dataset

The dataset contains labeled images of popular street foods (e.g., tacos, samosas, takoyaki) across different cuisines.

    Source: kagglehub.dataset_download("nikolasgegenava/popular-street-foods")

    Size: X = 3674 images, Y = 20 classes

    Labels: Organized by food type (e.g popular_street_foods/dataset/Tacos .. popular_street_foods/dataset/Shawarma etc)

🧠 Model Details

    Architecture: CNN (e.g., EfficientNetB0, Tensorflow)

    Training:

        Transfer learning (pretrained on ImageNet)

        Data augmentation (RandomFlip, RandomRotation)

    Metrics: Accuracy

📊 Results on validation data with GPU usage
  Model	Accuracy	Training Time

  CNN (Scratch)	35%	at 5.5 min,
  CNN (Data Augmentation)  44% at 9.3 min,
  EfficientNetB0	79%	at 2.7 min


📜 License

MIT License
🙌 Contributing

PRs welcome! Open an issue for suggestions or bugs.
