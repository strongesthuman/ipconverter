# ipconverter
Simple functions to add into .bashrc to convert IP address into binary, hexadecimal, decimal, octal formats and viceversa

# Setup

You can download the file (ipconverter) that has functions directly from above or if you're a linux geek and want to download the file from terminal only, 

<pre><code> wget https://raw.githubusercontent.com/bug-hunter-karna/ipconverter/master/ipconverter </code></pre>

Append the functions from <code>  ipconverter </code> to <code> \~/.bashrc </code>  or <code>\~/.bash_profile</code>

<pre><code> cat ipconverter >> ~/.bashrc </code></pre>

Load the <code>  ~/.bashrc </code>  file

<pre><code> source ~/.bashrc </code></pre>

# Usage

## IP to (Hexadecimal + Decimal + Octal + Binary) 

<pre><code> ip2all 127.0.0.1 </code></pre>

## Hexadecimal to IP

<pre><code> hex2ip 7F000001 </code></pre>

## Decimal to IP

<pre><code> dec2ip 2130706433 </code></pre>

## Octal to IP

<pre><code> oct2ip 017700000001 </code></pre>

## Binary to IP

<pre><code> bin2ip 1111111000000000000000000000001 </code></pre>


# Screenshot of Usage

<p align="center">
  
<img src="https://github.com/bug-hunter-karna/ipconverter/blob/master/ipconverter.png" height="400" width="700">

</p>


## Thank you :)

I just wanted to make it easier to convert IP address format rather than going to different websites for conversion. These formats (decimal, octal, hexadecimal etc) can be used to bypass blacklisted IP addresses while trying SSRFs.
