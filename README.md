# School Performance Analysis

This repository contains an analysis of school performance metrics, focusing on various factors such as school type, total students, total school budget, per student budget, average math score, average reading score, percentage passing math, percentage passing reading, overall passing rate, spending ranges per student, and school size. The goal is to identify trends and insights into how different factors affect school performance.

## Data Summary

- **School Type**: Public and Charter
- **Total Students**: Ranges from 427 to 4976
- **Total School Budget**: Varies significantly between schools
- **Per Student Budget**: Ranges from 578 to 655
- **Average Math Score**: Ranges from 76 to 83
- **Average Reading Score**: Ranges from 80 to 84
- **% Overall Passing**: Ranges from 52 to 91
- **School Size**: Categorized as Small (<1000), Medium (1000-2000), Large (2000-5000)

## Analysis

### Observable Trends

1. **Impact of School Type on Performance**:
   - The data indicates that charter schools tend to have higher average math and reading scores compared to public schools within this dataset. Especially math, with charter math scores averaging 83% and public schools averaging 77%. Similarly, charter schools have higher average reading scores (84%) compared to public schools (81%). This suggests that charter schools may be performing better academically than public schools, at least in terms of average scores.

2. **Correlation Between School Size and Test Scores**:
   - The data shows a potential correlation between school size and test scores. The schools in the dataset are categorized into three groups "Small" (<1000 students), "Medium" (1000-2000 students), and "Large" (2000-5000 students). The dataset indicates that small and medium schools are both performing at higher levels in terms of math and reading scores than Large schools. Further analysis with other data points would be needed to draw definitive conclusions, but this initial observation suggests that school size is possibly a limiting factor in achieving high academic performance.

## Usage

To run the analysis, you'll need to have Python, Jupyter Notebook, and the necessary packages installed. Follow the steps below to set up the environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/jhammans/pandas-challenge.git
   cd python-challenge/PyCitySchools
   ```

To run the analysis, execute the `PyCitySchools_Notebook.ipynb` notebook.

## Data

The data used for this analysis is included in the `Resources/` directory. Make sure to update the data files as needed to reflect the most recent and accurate information.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any questions or inquiries, please contact [Jeff Hammans](mailto:hef1125@hotmail.com).
