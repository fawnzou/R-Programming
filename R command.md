### 1. read.csv("absolute direcotory of the file")
### 2. getwd() ----get the current directory
### 3. setwd("C:/Users/fawnz/Downloads")-----find the data directory,and change directory temporaryly
### 4. subset(filename, columnname == 1)
### 5. filename[filename$columnname == 1, columns]
### 6. table(filename$columnname)  -----sort of like value_counts() in pandas
### 7. summary(filename) ------sort of line describe() in pandas
### 8. levels(filename$columnname)------like unique() in pandas
### 9. str(filename)
### 10. Set leverl order
        filename$column <-factor(filename$column,levels = c(.........),ordered=T )
### 11. list.files('C:/Users/fawnz/Downloads')
### 12. ggsave() will save the last plot created.
        For example...
        qplot(x = price, data = diamonds)
        ggsave('priceHistogram.png')
        getwd()-----to check the directory of this graph
