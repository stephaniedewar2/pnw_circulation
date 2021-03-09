# Readme



## Table of Contents

- Naming
- Normalization
- Data Dictionary
- Structured Metadata
- Contact Information

## Normalization

Normalization was done using a z-score. By using a z-score, it is easy to tell which fields each state is above and below average in in terms of circulation, and by how much. Each number represents the distance from the mean in standard deviations, and the positive or negative tells you whether the number is above or below that mean. That average for each categroy for the entire US in 2018 was used as the mean for caluclating the z-scare. 

## Naming

The files are named using the following formula: 

      projecttitle.year.datatype
      
For this project, the file with always start with pnwcirc, followed by the year, and then closed with either "normal" or "raw. The project title was included in order to differentiate the file from other projects. 


## Data Dictionary

| **Variable** | **Variable label** | **Variable type** | **Allowed Values** | **Description** |
| --- | --- | --- | --- | --- |
| **State** |	state |	string |	two letter state abbreviations | abbreviations for US state data is from |
| **Physical** | Book |	bookPH |	number |	any number |	circulation of physical books in 2018 |
| **eBook** |	bookDL |	number |	any number | circulation of ebooks in 2018 |
| **Physical** | audio |	audioPH |	number	|any number | circulation of audio content in 2018| 
| **Downloaded audio** |	audioDL |	number |	any number |	circulation of downloadable audio in 2018 |
| **Physical video** |	videoPH	| number |	any number |	circulation of physical video in 2018 |
| **Downloaded video**|	videoDL |	number |	any number |	circulation of downloadable video in 2018 |
| **Z-score of Physical Book** |	zbookPH |	number |	Integer between -3 and +3 |	normalized circulation of physical books in 2018 |
| **Z-score of eBook** |	zbookDL	| number |	Integer between -3 and +3 |	normalized circulation of ebooks in 2018 |
| **Z-score of Physical audio** |	zaudioPH |	number |	Integer between -3 and +3 |	normalized circulation of audio content in 2018 |
| **Z-score of Downloaded audio** |	zaudioDL	| number	| Integer between -3 and +3	| normalized circulation of downloadable audio in 2018 |
| **Z-score of Physical video** | zvideoPH |	number	| Integer between -3 and +3	| normalized circulation of physical video in 2018 |
| **Z-score of Downloaded video** | 	zvideoDL |	number |	Integer between -3 and +3	| normalized circulation of downloadable video in 2018 |


## Structured Metadata

| **Attribute** | **Value** |
| --- | --- | 
| **conformsTo** | https://project-open-data.cio.gov/v1.1/schema |
| **accessLevel** | public |
| **fn** | Stephanie Dewar |
| **hasEmail** | mailto:dewars@uw.edu |
|
| **description** | This dataset contains circulation information for public libraries in the Pacific Northwest (Washington, Idaho, and Oregon) for the year 2018. |


## Contact Information

You can reach me at dewars@uw.edu
