To study the intermediately created files we use the commands on terminal  : 
	
	1. gcc -save-temps filename.c
			: This would create for you, all the intermediate files required that 				  are filename.o, filename.i, filename.s
	2. vi filename.s filename.i filename.s
			: This would allow you to read the contents of above .o, .i, .s files
			  Note :- You can use any editor to do this, here we have used vim.
	3. objdump -l -d -r filename.o 
			: This is to read the dumps of filename.o file, as any text editor is 
			  not suitable for the purpose of reading those files.


Hope this helps !!!
Cheers!!!
 
