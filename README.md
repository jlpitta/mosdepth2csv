# Description
"Mosdepth2csv" is a script developed to process files named "thresholds.bed.gz" generated by the mosdepth tool, which is configured with the '--threshold' parameter. The purpose of this script is to extract relevant information from these files and transform it into CSV (Comma-Separated Values) format. Subsequently, these CSV files are bundled and compressed into a zip file for more convenient storage or distribution. This script serves as a tool for converting and organizing data outputted by mosdepth into a more accessible and manageable format.

# Usage:

To use mosdepth, first download the script via git clone:
```
git clone https://github.com/jlpitta/mosdepth2csv.git
```

Inside the newly downloaded mosdepth2csv directory, you can find not only the mosdepth2csv script but also some "thresholds.bed.gz" files that serve as example inputs. Additionally, there is a file named Mosdepth_Feb29_094836.zip, which is an example output generated by the script. The naming format of the output indicates the day and time when the file was created (in this example, February 29th at 09:48:36). This is useful for easily distinguishing the results of various script executions.

To test the script, simply run the mosdepth2csv script with one of the options below:
```
./mosdepth2Csv
```
or
```
bash mosdepth2Csv
```
To facilitate the use of the script, add the script's path to the PATH environment variable or create a symbolic link in the user's /bin folder.

To run mosdepth2csv on your data, navigate to the directory containing the results generated by mosdepth (with files named "thresholds.bed.gz"). Run the script from within this directory, either by providing the full path to the script or simply typing "mosdepth2csv" if the script is in the PATH or added to the user's /bin folder.
