# concurrent-activity-recognition

This code implements two models from two papers: "Recognition of Multiple Overlapping Activities Using
Compositional CNN-LSTM Model" and "Deep convolutional neural networks on multichannel time series for human activity recognition".

The dataset required is zipped under 'dataset.zip'. It only contains data from subject 3. To clean and parse the data, simply run 'datacleaning.ipynb'. You can change the constants accordingly. One thing to note is that in cell 5, if you want to split the dataset based on multiple labels, you need to comment/uncomment related lines.

To do the modeling, you can run 'modeling.ipynb'. You can also change the constant accordingly. The important thing is the LABEL_INDEX. It is used to determine which label you select. If it is multi-label, you don't need to worry about that. Instead, you need to comment/uncomment the lines marked as 'for 1/2 label'.

All models are saved under models/ directory with their date of creation appended for easier tracking purpose
