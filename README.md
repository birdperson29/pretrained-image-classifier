#Pet Image Classifier 
This project is designed to classify images of pets using a pre-trained Convolutional Neural Network (CNN) model. It compares the model's classifications to the true identity of the pets in the images, and provides a summary of the model's performance on the image classification task.

### The primary objective of this project is to classify pet images by extracting the pet labels from the image filenames and comparing the model's predictions to the true labels. We aim to determine which of the three different CNN model architectures provides the best classification performance. 

To run this program, you need to provide the following command line arguments:
--dir (or --directory): The directory containing the pet images.
--arch (or --model): The CNN model architecture to use for classification.
--dogfile: A file that contains a list of dog names for reference.

## Components: 
    get_input_args.py: This script retrieves the command line arguments from the user.

    get_pet_labels.py: It extracts pet labels from image filenames and creates a results dictionary.

    classify_images.py: This script uses the specified CNN model to classify the pet images and adds the results to the results dictionary.

    adjust_results4_isadog.py: It adjusts the results to determine if the classifier correctly classified images as "a dog" or "not a dog."

    calculates_results_stats.py: This script calculates summary statistics, including counts and percentages of correct classifications.

    print_results.py: It prints the summary results, incorrect classifications of dogs (if requested), and incorrectly classified breeds (if requested).


