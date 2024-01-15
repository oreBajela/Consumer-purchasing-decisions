# Consumer-purchasing-decisions
This project is an investigation into who has more influence on consumer purchasing decisions- celebrities or social media influencers

In today's ever changing landscape of advertising and marketing, understanding the factors that influence consumer purchasing decisions has become increasingly important. As the digital realm continues to reshape the way brands connect with their audiences, it becomes increasingly essential to investigate the efficacy of different promotional strategies. This research project, therefore, aims to shed light on the pivotal question: Between celebrity promotion and influencer marketing, which has more influence on consumer purchasing decisions?

This research problem unfolds in the context of a rapidly changing marketing environment. Traditional advertising methods, such as television and print media, have witnessed a substantial shift towards digital platforms and social media. In this digital age, the power of endorsements is no longer restricted to celebrities who command a broad, but often distant, audience. It has now trickled down to a new class of influencers—individuals who may not have global fame but boast a deep and intimate connection with their followers, sometimes numbering in the millions. Understanding the relative impact of these two prominent promotional avenues, celebrities and influencers, is essential for marketers.  Within this context, several gaps in knowledge emerge. While prior research has explored the impact of celebrity endorsements and influencer marketing independently, a comprehensive comparison of these two promotional strategies remains limited. Furthermore, most existing studies rely on self-reported data or small-scale surveys, which may not fully capture the nuanced decision-making processes of consumers in the real world. 
	
To address these gaps, our research aims to  create a Python-based data analysis that will allow us to give a comprehensive answer to our research question. Our methodology will involve the use of various API’s as well as visualization techniques and  probability modeling. By integrating these diverse methods, we aim to provide a holistic perspective on the influence of celebrity promotion and influencer marketing on consumer purchasing decisions. In doing so, we hope to deliver insights that can guide marketing strategies, inform decision-makers, and contribute to the discussion on the evolving world of advertising practices. All analysis, insights and conclusions can be found in the final project file. 

#Technologies used
Python: The primary programming language used for data analysis, visualization, and manipulation. Python's versatility and extensive libraries make it a suitable choice for handling various aspects of this project.

Google Trends:Google's tool used to analyze the popularity of search queries over time. Data from Google Trends was crucial for understanding the search volumes related to skincare brands during different promotional periods.

Instagram API: he Instagram API (Application Programming Interface) was employed to gather data related to influencers and celebrities associated with the skincare brands under investigation. This data provided insights into the social media impact of endorsements.

Data Visualization Libraries (e.g., Matplotlib):  Matplotlib, a Python library, was utilized to create line graphs for visualizing the relationship between search trends and campaign periods. Visualizations are essential for interpreting and presenting complex data patterns effectively.

Jupyter Notebooks:  Jupyter Notebooks were likely used for interactive and iterative data analysis. They provide an environment where code, visualizations, and text explanations can coexist, promoting a clear and reproducible analysis process.

Determ (AI Media Monitoring and Analytics):determ, a company specializing in AI media monitoring and analytics, was referenced in the project for additional insights. This external tool contributes to the validation and context of the project's findings.


#Software requirements
To successfully run and reproduce the analyses conducted in this project, ensure that the following software is installed on your system:

Python (version 3.6 or later): To install, visit the official Python website: Python Downloads. Follow the installation instructions for your operating system.
Verify the installation by running the command python --version or python3 --version in your terminal.

Jupyter Notebooks: Install Jupyter Notebooks using pip (Python's package installer) with the command: pip install notebook.
Start Jupyter Notebooks by running jupyter notebook in your terminal. Access the Jupyter environment through your web browser.

Matplotlib Library: Install Matplotlib using pip with the command: pip install matplotlib.

Google Trends Data:
All relevant google trend data is in the file section but if you want to see for yourself from the dirsct source. Visit Google Trends in your web browser.
Manually input and download relevant search query data.

Instagram API:All information derived from the instagram api is in the file section. However, to retrieve this information from the direct source, Apply for access to the Instagram Graph API on the Facebook for Developers website.
Obtain necessary credentials and permissions.

Data Analysis Libraries (e.g., pandas, numpy):Install necessary data analysis libraries using pip with commands like pip install pandas numpy.

Statistical Libraries (e.g., scipy):Install statistical libraries using pip with commands like pip install scipy.


# Usage instructions
Clone the Repository
Clone this GitHub repository to your local machine using the following command:

bash
git clone https://github.com/oreBajela/Consumer-purchasing-decisions.git
Replace your-username and your-repository with your GitHub username and the repository's name.

2. Set Up Virtual Environment (Optional but Recommended): It's recommended to use a virtual environment to manage project dependencies. Navigate to the project directory and create a virtual environment:
cd your-Consumer-purchasing-decisions
python -m venv venv
Activate the virtual environment:
On Windows:
bash
.\venv\Scripts\activate
On macOS/Linux:
bash
source venv/bin/activate

4. Install Dependencies
Install the required Python packages by running:

bash
pip install -r requirements
This will install the necessary libraries and tools specified in the  software requirements.

4. Acquire Data
Collect Google Trends data manually by visiting Google Trends.
Obtain Instagram API credentials by applying on the Facebook for Developers website.

5. Run Jupyter Notebooks
Start Jupyter Notebooks in the project directory:

bash
Access the Jupyter environment through your web browser. Open and run the relevant notebooks (analysis.ipynb, methods.ipynb) to reproduce the analyses.

6. Interpret Results
Review the generated visualizations, statistical analyses, and insights within the Jupyter Notebooks. Interpret the results and draw conclusions based on the comparison of influencer and celebrity promotions.


Maintenance and Documentation
Keeping the Project Up-to-Date
To ensure the project remains compatible with the latest libraries and tools, regularly check for updates to Update Dependencies and  Update the Python packages to their latest versions.

Review Codebase: Periodically review the codebase for any deprecated or outdated syntax. Address and modify code accordingly.

Check External APIs: If external APIs (e.g., Google Trends, Instagram API) are used, verify if any changes in their endpoints or authentication methods require updates in your code.

Documentation
Maintain comprehensive documentation to facilitate understanding and collaboration. Update the documentation whenever there are significant changes or additions to the project. 
The code contains clear comments to explain complex sections, logic, or any unconventional approaches.
Notebook Descriptions: Within Jupyter Notebooks (analysis.ipynb, methods.ipynb), we provide detailed markdown descriptions for each section and larify the purpose of the code, the methodology employed, and the interpretation of results.
Data Sources: We keep a detailed record of the sources for all data used in the project. If new data is added or if there are changes in data collection methods, update this section.


Contributing 
I welcome contributions from the community to enhance and improve this project. If you would like to contribute, please follow these guidelines:

Reporting Issues: If you encounter any issues or bugs, please open an issue on the project's GitHub repository. Provide a detailed description of the problem, including steps to reproduce it.

Suggesting Enhancements: If you have ideas for enhancements or new features, feel free to submit them as GitHub issues.

Code Contributions: If you would like to contribute code to the project, please follow these steps: Fork the repository and create a new branch for your feature or bug fix. Ensure that your code adheres to the project's coding standards and style guidelines. Submit a pull request with a clear description of the changes and the problem they solve.

Testing: If you are contributing code, please ensure that your changes are accompanied by appropriate tests. This helps maintain the project's stability and reliability.

Documentation: Contributions to project documentation, including the README, are also highly appreciated. If you notice any gaps or inaccuracies in the documentation, please submit a pull request to address them.
