# nitcbase
### Record block structure
#### Header
attribute size = 16 bytes    
0 - 3 bytes: type of block (REC, IND_INTERNAL,IND_LEAF)  
4 - 7: parent pointer  
8 - 11: left block number  
12-15: right block number  
16 - 19: number of records in the block  
20 - 23: Number of attributes that are stored in the block  
24-27: number of slots in the block  
28-31: reserved for future use

