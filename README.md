Description
DocOrganizer is a Python application designed to process and organize Word documents based on section titles, and generate proposal summary documents. It features an interactive user interface built with Streamlit, allowing users to easily categorize files and create summary documents.

Features
File Categorization: Organizes Word documents into sub-folders based on section titles.
Proposal Summary Document Creation: Generates a Word document summarizing proposals for a user-selected section.
User-Friendly Interface: Streamlit-based interface for easy interaction and control.

Usage
Open the Streamlit interface.
Upload a folder of Word documents.
Select a section to generate the proposal summary document.
The script will categorize the files and generate the summary document.

Examples
Below is an example of how to use DocOrganizer:

from docorganizer import categorize_files, generate_summary

# Example folder path
folder_path = '/path/to/word/documents'

# Categorize files
categorize_files(folder_path)

# Generate summary for section 8.3.4
generate_summary(folder_path, '8.3.4')
