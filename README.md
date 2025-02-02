# Sorting Visualizer

Welcome to **Sorting Visualizer**! This interactive web application helps you understand how different sorting algorithms work by providing a visual representation of the sorting process. Watch in real-time as the algorithms rearrange arrays, making it easier to grasp their inner workings and compare their efficiencies.

🔗 **Live Demo**: [https://sorting-visualizer-ncyx.onrender.com](https://sorting-visualizer-ncyx.onrender.com)

## Features
- **Multiple Sorting Algorithms**: Visualize popular sorting algorithms including Bubble Sort, Heap Sort, Insertion Sort, Merge Sort, Quick Sort, and Selection Sort.
- **Customizable Input**: Generate random arrays or input your own custom array to sort.
- **Adjustable Controls**: 
  - Control the animation speed to watch the sorting process in detail or see it work quickly
  - Modify the size of randomly generated arrays
  - Real-time visualization of the sorting process
- **Interactive UI**: Clean and user-friendly interface built with React and CSS.

## Technologies Used
- **Frontend**: React.js for building the user interface
- **Styling**: Custom CSS for styling components
- **Logic**: Plain JavaScript for implementing sorting algorithms
- **Animation**: JavaScript for handling sorting animations

## Supported Algorithms
The visualizer currently implements the following sorting algorithms:

- **Bubble Sort**: Simple comparison-based algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
- **Heap Sort**: Comparison-based sorting algorithm that uses a binary heap data structure to build a max-heap and repeatedly extract the maximum element.
- **Insertion Sort**: Builds the final sorted array one item at a time by repeatedly inserting a new element into the sorted portion of the array.
- **Merge Sort**: Efficient divide-and-conquer algorithm that recursively breaks down the array into smaller subarrays, sorts them, and then merges them back together.
- **Quick Sort**: Fast divide-and-conquer algorithm that works by selecting a 'pivot' element and partitioning the array around it.
- **Selection Sort**: Simple comparison-based algorithm that divides the input list into a sorted and an unsorted region and repeatedly selects the smallest element from the unsorted region.

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/sorting-visualizer.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd sorting-visualizer
   ```

3. **Install dependencies and build**:
   ```bash
   npm run build
   ```

4. **Start the application**:
   ```bash
   npm run start
   ```
   The application will launch in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Usage

1. **Generate Random Array**:
   - Click the "Generate New Array" button to create a random array
   - Use the size slider to adjust the number of elements in the array

2. **Custom Array**:
   - Enter your own array elements in the input field
   - Click "Set Array" to visualize your custom array

3. **Control Visualization**:
   - Use the speed slider to adjust the animation speed
   - Select any sorting algorithm to start the visualization
   - Watch the sorting process in real-time

## Contributing
We welcome contributions to improve the Sorting Visualizer! Here's how you can help:

1. Fork the repository
2. Create your feature branch:
   ```bash
   git checkout -b feature/YourAmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourAmazingFeature
   ```
5. Open a Pull Request



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support
If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/your-username/sorting-visualizer/issues) page
2. Open a new issue if your problem hasn't been reported
3. Provide detailed information about your problem

