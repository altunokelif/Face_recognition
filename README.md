# The-Olivetti-Dataset

As described on the original website:


Our Database of Faces, (formerly 'The ORL Database of Faces'), contains a set of face images taken between April 1992 and April 1994 at the lab. The database was used in the context of a face recognition project carried out in collaboration with the Speech, Vision and Robotics Group of the Cambridge University Engineering Department.

There are ten different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions (open / closed eyes, smiling / not smiling) and facial details (glasses / no glasses). All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position (with tolerance for some side movement). A preview image of the Database of Faces is available.

The files are in PGM format, and can conveniently be viewed on UNIX (TM) systems using the 'xv' program. The size of each image is 92x112 pixels, with 256 grey levels per pixel. The images are organised in 40 directories (one for each subject), which have names of the form sX, where X indicates the subject number (between 1 and 40). In each of these directories, there are ten different images of that subject, which have names of the form Y.pgm, where Y is the image number for that subject (between 1 and 10).

The database can be retrieved from http://www.cl.cam.ac.uk/Research/DTG/attarchive:pub/data/att_faces.tar.Z as a 4.5Mbyte compressed tar file or from http://www.cl.cam.ac.uk/Research/DTG/attarchive:pub/data/att_faces.zip as a ZIP file of similar size.

A convenient reference to the work using the database is the paper Parameterisation of a stochastic model for human face identification. Researchers in this field may also be interested in the author's PhD thesis, Face Recognition Using Hidden Markov Models, available from http://www.cl.cam.ac.uk/Research/DTG/attarchive/pub/data/fsamaria_thesis.ps.Z (~1.7 MB).

When using these images, please give credit to AT&T Laboratories Cambridge.

UNIX is a trademark of UNIX System Laboratories, Inc.

https://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html



Some results:

![Olivetti_LDA_table](https://user-images.githubusercontent.com/44237325/72207532-23a09580-34ab-11ea-8334-430ffe7b6460.PNG)
![Olivetti_LDA_chart](https://user-images.githubusercontent.com/44237325/72207529-226f6880-34ab-11ea-8143-77ce5c1e8573.PNG)
![Olivetti_LDA_transformedplot](https://user-images.githubusercontent.com/44237325/72207534-23a09580-34ab-11ea-9c6d-e500ec2b37b1.PNG)
![Olivetti_PCA_transformedplot](https://user-images.githubusercontent.com/44237325/72207523-213e3b80-34ab-11ea-84b1-62541430750d.PNG)
![Olivetti_SVM_chart](https://user-images.githubusercontent.com/44237325/72207528-226f6880-34ab-11ea-8854-82e09b6c5f94.PNG)
![Olivetti_SVM_table](https://user-images.githubusercontent.com/44237325/72207531-2307ff00-34ab-11ea-9da4-8d66f4dc5d13.PNG)
![Olivetti_PCA_SVM_chart](https://user-images.githubusercontent.com/44237325/72207526-21d6d200-34ab-11ea-8dd5-1e14dacb3faf.PNG)
![Olivetti_PCA_SVM_summarytable](https://user-images.githubusercontent.com/44237325/72207527-226f6880-34ab-11ea-9b7b-993c1fe4c75c.PNG)
![Olivetti_PCA_SVM_table](https://user-images.githubusercontent.com/44237325/72207530-2307ff00-34ab-11ea-80c7-177e2fb71bca.PNG)
![Olivetti_best_chart](https://user-images.githubusercontent.com/44237325/72207524-21d6d200-34ab-11ea-87a4-3453cd44babb.PNG)
![Olivetti_besttable](https://user-images.githubusercontent.com/44237325/72207525-21d6d200-34ab-11ea-9599-5f7664b1eb12.PNG)
