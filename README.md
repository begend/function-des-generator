# Generate Function Description – Atom Plugin

Package that generates comments describing functions.

Select the function text and activate with `cmd + ctrl + /`

Currently only works for languages that support `/* */` style comments.

before:
![A screenshot](http://g.recordit.co/rZT2QkanQt.gif)

my :
    
demo:
    /**
     * @brief : Autogenerates function contract comments
     * @params : [in|out]  : 
     * @return :  int
     * @retval :
     **/
    int init_log();

