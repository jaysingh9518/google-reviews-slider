# Google Reviews Slider

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

The **Google Reviews Slider** is a simple, elegant solution for showcasing Google Business reviews on your website. This slider fetches and displays reviews from your Google Business profile, providing an interactive and visually appealing way to highlight customer feedback.

## Features

- Fetches Google Business reviews dynamically
- Responsive design
- Easy integration into any website
- Customizable appearance
- Automatic sliding with pause on hover
- Lightweight and fast

## Demo

Check out the [live demo](https://jaysingh9518.github.io/google-reviews-slider/) to see the slider in action.

## Installation

### Prerequisites

- A Google Business profile with publicly visible reviews
- Google Places API key

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/jaysingh9518/google-reviews-slider.git
    ```

2. Navigate to the project directory:
    ```bash
    cd google-reviews-slider
    ```

3. Open `index.html` in a text editor and replace `'YOUR_GOOGLE_PLACES_API_KEY'` with your actual Google Places API key.

4. Customize the slider appearance in `style.css` if necessary.

5. Deploy the project files to your web server.

## Usage

To integrate the Google Reviews Slider into your website:

1. Include the necessary HTML snippet where you want the slider to appear:
    ```html
    <div id="google-reviews-slider"></div>
    ```

2. Ensure you have included the required CSS and JS files in your HTML:
    ```html
    <link rel="stylesheet" href="path/to/style.css">
    <script src="path/to/script.js"></script>
    ```

3. Initialize the slider in your JavaScript:
    ```javascript
    document.addEventListener("DOMContentLoaded", function() {
        initGoogleReviewsSlider();
    });
    ```

## Configuration

You can configure various aspects of the slider by modifying the parameters in `script.js`:
- `numReviews`: Number of reviews to display
- `slideInterval`: Time interval between slides in milliseconds
- `showRating`: Display star rating (true/false)

## Contributing

Contributions are welcome! If you have suggestions, bug reports, or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## Acknowledgments

- [Google Places API](https://developers.google.com/places/web-service/overview)
- [Slick Carousel](https://kenwheeler.github.io/slick/)

## Contact

For more information, please visit my [GitHub profile](https://github.com/jaysingh9518) or [portfolio website](https://jaysingh9518.github.io/).
