# Google Reviews Slider

A simple and customizable Google Reviews slider widget that can be easily integrated into any website. Display Google reviews in a stylish, dynamic, and responsive slider to boost credibility and user engagement.

## Features

- Fetch and display Google reviews dynamically
- Responsive design that works on all devices
- Customizable slider settings (speed, transition, etc.)
- Easy integration with any website

## Demo

[Check out the live demo](https://jaysingh9518.github.io/google-reviews-slider/)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/jaysingh9518/google-reviews-slider.git
    ```
2. Navigate to the project directory:
    ```sh
    cd google-reviews-slider
    ```
3. Open `index.html` in your browser to see the slider in action.

## Usage

1. Include the required CSS and JavaScript files in your HTML:
    ```html
    <link rel="stylesheet" href="path/to/your/css/styles.css">
    <script src="path/to/your/js/script.js"></script>
    ```

2. Add the slider markup to your HTML:
    ```html
    <div id="google-reviews-slider">
        <!-- Reviews will be dynamically loaded here -->
    </div>
    ```

3. Initialize the slider in your JavaScript:
    ```javascript
    document.addEventListener('DOMContentLoaded', function() {
        GoogleReviewsSlider.init({
            apiKey: 'YOUR_GOOGLE_API_KEY',
            placeId: 'YOUR_GOOGLE_PLACE_ID',
            numReviews: 5,
            sliderSettings: {
                speed: 500,
                transition: 'slide'
            }
        });
    });
    ```

## Configuration

- `apiKey`: Your Google API key.
- `placeId`: The Place ID of your business.
- `numReviews`: Number of reviews to fetch and display.
- `sliderSettings`: Customize the slider settings (speed, transition, etc.).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any inquiries or support, please contact [Jay Prakash](https://jaysingh9518.github.io/) or open an issue in this repository.
