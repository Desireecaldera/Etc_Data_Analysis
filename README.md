The Entertainment Technology Center (ETC) at Carnegie Mellon University (CMU) is a two-year Masters program founded in 1998 that focus on building transformational games, innovating by design, and interactive storytelling. With one preparatory semester and three project semesters, teams of 40% technical, 40% art, and 20% of an alternatively focused students by composition, participate in 14-week project development. Our research advisor and professor Dr. Eric Kaltman has been given copies of their project development files and folders up until this last Spring 2022 semester to perform analysis and research. This data comprises all project folders, data, source code, and all assets.

There has been some work prior to our involvement in this research. This can be split up into two parts, the ETC Past Project Listing portion and the DROID file analysis. The ETC Past Project Listing is a major endeavor of obtaining all information about those projects, such as project name, semester, year, advisors, members, client(s), technologies used, meta categories, etc. Much of the data was given to us in an unorganized fashion, and we needed to determine many of those details by investigation.

The DROID file analysis focused on the use of a tool developed by the UK National Archives called DROID (Digital Record Object Identification Program), which uses file extensions, binary signatures and more to identify files to their PRONOM file format identifier. PRONOM is the technical registry detailing information about the structure of those file formats and the software which uses them. Thus, the DROID file analysis portion was focused on the development of a methodology to analyze the data.  Multithreaded Python scripts were created to analyze the files as quickly as possible to create comma-separated-value (CSV) files for each project or semester. This part of the work also combined the ETC Past Project Listing with this analysis to initially create a SQLite3 database file of more than 6GB of metadata.

Two sets of analysis have already been performed, a partial content analysis [1] and a full content profile [2] culminating in two research papers. The partial  content analysis consisted of four projects, including one animation project and three games. The animation project consisted of 275GB of 293GB of project data. They discovered 222 distinct file extensions, 119 were not identified. In the full content profile, they found 9.2 million files, and about 4,982 file extensions. 3,425 file extensions were not identified, about four million files or 44% of the data.
