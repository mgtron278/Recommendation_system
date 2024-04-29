
# Fashion Recommendation System using Convolutional Neural Networks (CNN)

This repository contains code for a fashion recommendation system based on Convolutional Neural Networks (CNN). The system takes an input image of a fashion item and recommends similar fashion items from a dataset using image similarity calculated via CNN features.

## Project Explanation

Fashion recommendation systems play a crucial role in e-commerce platforms, helping users discover new items that match their preferences. This project aims to build a recommendation system for fashion items using deep learning techniques.

### How It Works

1. **Feature Extraction with VGG16:**
   - Utilizes the VGG16 pre-trained model, a popular CNN architecture, for feature extraction from fashion images.
   - Extracted features capture high-level representations of fashion items, enabling comparison and similarity calculation.

2. **Image Similarity Calculation:**
   - Calculates image similarities between the input image and the dataset images using cosine distance.
   - Cosine distance measures the angle between feature vectors, providing a measure of similarity between images.

3. **Recommendation Generation:**
   - Recommends top N similar fashion items based on the input image.
   - Displays input image alongside recommended items for easy comparison.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset:**
   Ensure your dataset of fashion images is stored in a directory named `women fashion`.

4. **Run the recommendation system:**
   Run the `recommend_fashion_items_cnn.py` script, providing the path to the input image.
   ```bash
   python recommend_fashion_items_cnn.py
   ```

## Usage

- Modify the input image path in `recommend_fashion_items_cnn.py` to test with different fashion items.
- Adjust the `top_n` parameter in the recommendation function to change the number of recommendations.

## Contributing

Contributions are welcome! If you'd like to add new features, improve the existing codebase, or fix issues, feel free to open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by the need for personalized fashion recommendation systems.


