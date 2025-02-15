# 🐍 IPython Handbook

## 📝 Description
This Python script demonstrates **interactive computing** and **debugging** using **IPython**. It covers key features such as magic commands, profiling, and debugging tools. The script also includes examples of timing code execution, memory profiling, and line profiling.

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/navidfalah/ipython-handbook.git
   cd ipython-handbook
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Install additional libraries:
   ```bash
   pip install ipython line_profiler memory_profiler
   ```

## 🚀 Usage
1. Run the script:
   ```bash
   python ipython_handbook.py
   ```
2. The script will:
   - Demonstrate IPython magic commands.
   - Profile code execution using `%timeit` and `%prun`.
   - Perform line profiling and memory profiling.
   - Debug code using `%debug`.

## 📂 File Structure
```
ipython-handbook/
├── ipython_handbook.py  # Main script
├── README.md            # This file
├── requirements.txt     # Dependencies
└── data/                # (Optional) Data folder for local inputs
```

## 🧩 Key Features
- **Magic Commands**:
  - Use `%run`, `%timeit`, `%prun`, `%debug`, and other IPython magic commands.
- **Profiling**:
  - Time code execution with `%timeit`.
  - Profile function calls with `%prun`.
  - Perform line profiling with `%lprun`.
  - Profile memory usage with `%memit`.
- **Debugging**:
  - Debug code using `%debug` and `%xmode`.

## 📊 Example Outputs
1. **Magic Commands**:
   - `%run myscript.py` to execute a Python script.
   - `%timeit sum(range(100))` to time code execution.
2. **Profiling**:
   - `%prun sum_of_lists(1000000)` to profile function calls.
   - `%lprun -f sum_of_lists sum_of_lists(5000)` for line profiling.
   - `%memit sum_of_lists(1000000)` for memory profiling.
3. **Debugging**:
   - `%debug func2()` to debug a function.

## 🤖 Libraries Used
- **IPython**: For interactive computing and debugging.
- **line_profiler**: For line-by-line profiling.
- **memory_profiler**: For memory usage profiling.

## 📈 Performance Metrics
- **Efficiency**: Optimized for interactive computing and debugging.
- **Flexibility**: Supports a wide range of profiling and debugging tools.

## 🛠️ Dependencies
- Python 3.x
- Libraries:
  - `ipython`, `line_profiler`
  - `memory_profiler`

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👤 Author
- **Name**: Navid Falah
- **GitHub**: [navidfalah](https://github.com/navidfalah)
- **Email**: navid.falah7@gmail.com
