Download Link: https://assignmentchef.com/product/solved-cse102-homework-5
<br>
New Type Coronavirus (Covid-19) entered our lives and unfortunately almost brought our lives to a halt! The whole world is trying to fight this virus and there are hundreds of news about it every day. We want to develop a program to follow these news and to find confidential information in the news.

<strong><u>Please note that the main function of this program will consist only of calling the menu () function.</u> </strong>

<strong>Part 1.</strong><strong> </strong>Every day, 4 reliable and encrypted news texts are presented to the heads of state selected from thousands of Covid-19 related news. (Selected news of today is in the news folder.) The first line of news texts always includes the title of the news. The other lines are the content of the news text.

<ul>

 <li>First of all, you should list the headlines of news texts to produce the following output.</li>

 <li>Then, you should print the menu containing the actions that can be performed on the screen.</li>

 <li>If the user chooses the option ‘a’, you should ask which news text you want to read and then print the news text on the screen depending on that choice. After the news text is displayed, the user should be asked if he wants to continue reading. If it wants to continue, the initial menu should be displayed, otherwise the program should be finished.</li>

</ul>

Assume that the size of the text in the text files will be a maximum of 500 characters.

You should perform all selection operations within a menu () function, but for all other operations that should be done depending on these selections, you should design the functions whose prototype is given below.

void menu()

<strong>to read the news from the folder</strong>:

[This function reads the entire news text when the value of is_Only_title is 0, and only the title of the news text when 1 arrives.]

void read_news(char buffer[500], char file_path[10], int is_Only_Title)

<strong>Part 2.</strong><strong>      </strong>We also expect this program to keep track of what was previously read. You will need to use this information in both the ‘a’ option and the ‘b’ option.

<strong>Remember that! When we terminate the program and start it again, it must still be kept up to date if that news has been read! </strong>

If the user wants to read a previously read news in ‘a’ option, ‘This news has been read before. Do you want to read it again? ‘ You should warn him/her with the message. And if he/she wants to read it, you should bring that news text back to the screen. If he/she does not want to read, ‘Would you like to continue?’ If you want to continue, you should show the start screen again on the screen. If he doesn’t want to continue, ‘Good Bye!’ You can end the program with the message.

If the user chooses the option ‘b’, you should print the list of news read this time on the screen as shown in the image below.

When the program is opened and closed, it should be kept in a file such as a database, so that the information of the readers are not lost.

<strong>to append a character to the file: </strong>void append_file(char* file_path, char c)

<strong>When the reader reads the news and wants to read it at different times, you should make sure that it is not added once again to the news list read! </strong>




<strong>Part 3.</strong>Finally, you are expected to decrypt the passwords in the texts. Each news text has a ‘#’ sign placed at random points and a number next to it. These numbers are your magic numbers.

The process described below with your magic numbers will provide you with a variety of information.

()

Let      and

The hidden number from the 1st text file will always represent the number of tests performed.

The hidden number from the 2nd text will always represent the number of sick people.

The hidden number from the 3rd text will always represent the number of deaths.

The hidden number from the 4th text will always represent the expected number of sick people.

<strong>For reading the magic numbers : </strong>

void read_magic_numbers(char buffer_magic[10], char buffer_news[500])

<strong>For calculating the f(x) function : </strong>double f_func(int x)

<strong>For calculating the g(f(x)) function : </strong>

<strong> </strong>

double g_func(double f(int x), int a)

<strong> </strong>