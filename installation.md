## How to run the code
This is an executable Jupyter notebook. You can run and experiment with the code in a couple of ways: using free online resources (recommended) or on your own computer.

### Option 1: Running using free online resources<hr> 
Go to colab.research.google.com There go to File -> Open Notebook -> GitHub. There paste the following link
> https://github.com/mizerablepi/Video-games-sales-analysis/blob/main/Project_Video_game_sales_analysis.ipynb 

Click Import.<br>
Once the notebook is imported, click run all to run all cells, and view the outputs.

### Option 2: Running on your computer locally<hr>

Install Conda by following these instructions. Add Conda binaries to your system PATH, so you can use the conda command on your terminal.

Create a Conda environment and install the required libraries by running these commands on the terminal:

    conda create -n VG_analysis -y python=3.8 
    conda activate VG_analysis
    pip install jovian jupyter numpy pandas matplotlib seaborn opendatasets --upgrade

Press the "Code" button above to copy the command for downloading the notebook, and run it on the terminal. This will create a new directory and download the notebook. The command will look something like this:

    git@github.com:mizerablepi/Video-games-sales-analysis.git

Enter the newly created directory using cd directory-name and start the Jupyter notebook.

    jupyter notebook

You can now access Jupyter's web interface by clicking the link that shows up on the terminal or by visiting http://localhost:8888 on your browser. Click on the notebook file (it has a .ipynb extension) to open it.
