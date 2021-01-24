<div data-v-5e9078c0="" data-v-b06dc010="" class="QuestionsList"><div data-v-5e9078c0=""><h1 data-v-5e9078c0="">
      Top 12 Bit Manipulation interview
      questions and answers in 2021.
    </h1> <p data-v-5e9078c0="" align="center"><a data-v-5e9078c0="" href="https://devinterview.io/"><img data-v-5e9078c0="" src="https://source.unsplash.com/collection/52661698/700x350"></a></p> <p data-v-5e9078c0="">
      You can check all
      12
      Bit Manipulation interview questions here 👉
      https://devinterview.io/data/bitManipulation-interview-questions
    </p> <br data-v-5e9078c0=""> <div data-v-5e9078c0="" class="unit"><div><h2>🔹 1. What is Bit?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>A <strong>bit</strong> is a short for <strong>"binary digit"</strong>. It is the smallest unit of measurement in computer data. It contains a single binary value of 0 or 1. A single bit can define a boolean value of True (1) or False (0), but in computer memory, bits are often grouped together in 8-bit clusters called bytes. </p> <p>Since a <strong>byte</strong> contains eight bits that each have two possible values, a single byte may have 28 or 256 different values.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://www.devinterview.io" rel="noreferrer" target="_blank" title="What is Bit? Interview Questions Source To Answer">Devinterview.io</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 2. Name some bitwise operations you know</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><ul><li><strong>NOT ( ~ )</strong>: Bitwise NOT is an unary operator that flips the bits of the number i.e., if the ith bit is 0, it will change it to 1 and vice versa. </li><li><strong>AND ( &amp; )</strong>: Bitwise AND is a binary operator that operates on two equal-length bit patterns. If both bits in the compared position of the bit patterns are 1, the bit in the resulting bit pattern is 1, otherwise 0.</li><li><strong>OR ( | )</strong>: Bitwise OR is also a binary operator that operates on two equal-length bit patterns, similar to bitwise AND. If both bits in the compared position of the bit patterns are 0, the bit in the resulting bit pattern is 0, otherwise 1.</li><li><strong>XOR ( ^ )</strong>: Bitwise XOR also takes two equal-length bit patterns. If both bits in the compared position of the bit patterns are 0 or 1, the bit in the resulting bit pattern is 0, otherwise 1.</li></ul><pre><code><span class="token cMod">AND</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">1</span>      <span class="token cMod">OR</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">1</span>
<span class="token cBase">--</span><span class="token cBase">-</span><span class="token cBase">+</span><span class="token cBase">--</span><span class="token cBase">--</span>    <span class="token cBase">--</span><span class="token cBase">-</span><span class="token cBase">+</span><span class="token cBase">--</span><span class="token cBase">--</span>
  <span class="token cNum">0</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">0</span>       <span class="token cNum">0</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">1</span>
  <span class="token cNum">1</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">1</span>       <span class="token cNum">1</span><span class="token cBase">|</span><span class="token cNum">1</span> <span class="token cNum">1</span>

<span class="token cMod">XOR</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">1</span>     <span class="token cMod">NOT</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">1</span>
<span class="token cBase">--</span><span class="token cBase">-</span><span class="token cBase">+</span><span class="token cBase">--</span><span class="token cBase">--</span>    <span class="token cBase">--</span><span class="token cBase">-</span><span class="token cBase">+</span><span class="token cBase">--</span><span class="token cBase">-</span>
  <span class="token cNum">0</span><span class="token cBase">|</span><span class="token cNum">0</span> <span class="token cNum">1</span>        <span class="token cBase">|</span><span class="token cNum">1</span> <span class="token cNum">0</span>
  <span class="token cNum">1</span><span class="token cBase">|</span><span class="token cNum">1</span> <span class="token cNum">0</span></code></pre><ul><li><p><strong>Left Shift ( &lt;&lt; )</strong>: Left shift operator is a binary operator which shift the some number of bits, in the given bit pattern, to the left and append 0 at the end.</p></li><li><p><strong>Signed Right Shift ( &gt;&gt; )</strong>: Right shift operator is a binary operator which shift the some number of bits, in the given bit pattern, to the right, preserving the sign (which is the first bit)</p></li><li><p><strong>Zero Fill Right Shift ( &gt;&gt;&gt; )</strong>: Shifts right by pushing zeros in from the left, filling in the left bits with 0s</p></li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://www.hackerearth.com/practice/basic-programming/bit-manipulation/basics-of-bit-manipulation/tutorial/" rel="noreferrer" target="_blank" title="Name some bitwise operations you know Interview Questions Source To Answer">www.hackerearth.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 3. Explain what is Bitwise operation?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p><strong>Bitwise operators</strong> are used for <em>manipulating a data at the bit level</em>, also called as bit level programming. It is a fast and simple action, directly supported by the processor, and is used to manipulate values for comparisons and calculations.</p><p>On simple low-cost processors, typically, bitwise operations are substantially faster than division, several times faster than multiplication, and sometimes significantly faster than addition.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://en.wikipedia.org/wiki/Bitwise_operation" rel="noreferrer" target="_blank" title="Explain what is Bitwise operation? Interview Questions Source To Answer">en.wikipedia.org</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 4. What is a Byte?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>A <strong>byte</strong> is made up of 8 bits and the highest value of a byte is 255, which would mean every bit is set. We will look at why a byte's maximum value is 255 in just a second.</p><p>So if all bits are set and the value = 255 my byte would look like this:</p><div><table>
    <tbody>
        <tr> 
            <td colspan="11"> 
                1 Byte ( 8 bits )
            </td>
        </tr>
    <tr> 
        <td>
            Place Value
        </td>
        <td> 
          128
        </td>
        <td> 
          64
        </td>
        <td> 
          32
        </td>
        <td> 
          16
        </td>
        <td> 
          8
        </td>
        <td> 
          4
        </td>
        <td> 
          2
        </td>
        <td> 
          1
        </td>
        <td></td>
        <td></td>
    </tr>
    <tr> 
        <td>&nbsp;</td>
        <td> 
          <div align="center">1
        </div></td>
        <td> 
          <div align="center">1
        </div></td>
        <td> 
          <div align="center">1
        </div></td>
        <td> 
          <div align="center">1
        </div></td>
        <td> 
          <div align="center">1
        </div></td>
        <td> 
          <div align="center">1
        </div></td>
        <td> 
          <div align="center">1
        </div></td>
        <td> 
          <div align="center">1
        </div></td>
        <td>
          <div align="center">=
        </div></td>
        <td>255</td>
    </tr>
    </tbody>
</table>
<br>
Lets take it right to left and add up all those values together
1 + 2 + 4 + 8 + 16 + 32 + 64 + 128 = 255</div></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://github.com/BruceLampson/bitwise/blob/master/README.md" rel="noreferrer" target="_blank" title="What is a Byte? Interview Questions Source To Answer">github.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 5. Flip all bits in an integer</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div class="mb-2"><span class="h5">Problem</span></div><div><div class="AnswerBody"><p>I have to flip all bits in a binary representation of an integer. Given:</p><pre><code><span class="token cNum">10101</span></code></pre><p>The output should be</p><pre><code><span class="token cNum">01010</span></code></pre><p>What is the bitwise operator to accomplish this when used with an integer?</p></div></div><div><div class="AnswerBody"><p>Simply use the bitwise <strong>not</strong> operator <code>~</code>.</p><pre><code>int <span class="token cMod">flipBits</span><span class="token cBase">(</span><span class="token parameter">int n</span><span class="token cBase">)</span> <span class="token cBase">{</span>
    <span class="token cVar">return</span> <span class="token cBase">~</span>n<span class="token cBase">;</span>
<span class="token cBase">}</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/6351374/bitwise-operator-for-simply-flipping-all-bits-in-an-integer" rel="noreferrer" target="_blank" title="Flip all bits in an integer Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 6. What would the number 22 look like as a Byte?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>A byte is made up of 8 bits and the highest value of a byte is 255, which would mean every bit is set.</p><p>Now:</p><div><table>
    <tbody>
    <tr> 
    <td colspan="11"> 
    1 
    Byte ( 8 bits )
    </td>
    </tr>
    <tr> 
    <td>Place 
    Value</td>
    <td> 
    128
    </td>
    <td> 
    64
    </td>
    <td> 
    32
    </td>
    <td> 
    16
    </td>
    <td> 
    8
    </td>
    <td> 
    4
    </td>
    <td> 
    2
    </td>
    <td> 
    1
    </td>
    <td></td>
    <td></td>
    </tr>
    <tr> 
    <td>&nbsp;</td>
    <td> 
    <div align="center">0
    </div></td>
    <td> 
    <div align="center">0
    </div></td>
    <td> 
    <div align="center">0
    </div></td>
    <td> 
    <div align="center">1
    </div></td>
    <td> 
    <div align="center">0
    </div></td>
    <td> 
    <div align="center">1
    </div></td>
    <td> 
    <div align="center">1
    </div></td>
    <td> 
    <div align="center">0
    </div></td>
    <td>
    <div align="center">=
    </div></td>
    <td>
    <div align="center">22
    </div></td>
    </tr>
    </tbody>
</table>
<br></div><p>Lets take it right to left and add up all those values together:</p><p>128 <em> <code>0</code> + 64 </em> <code>0</code> + 32 <em> <code>0</code> + 16 </em> <code>1</code> + 8 <em> <code>0</code> + 4 </em> <code>1</code> + 2 <em> <code>1</code> + 1 </em> <code>0</code>   = 22  </p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://github.com/BruceLampson/bitwise/blob/master/README.md" rel="noreferrer" target="_blank" title="What would the number 22 look like as a Byte? Interview Questions Source To Answer">github.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 7. What is Bit Masking?</h2></div> <div>
    👉🏼 Check
    <a href="https://devinterview.io/data/bitManipulation-interview-questions">all 12 answers</a></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 8. Explain how XOR (^) bit operator works</h2></div> <div>
    👉🏼 Check
    <a href="https://devinterview.io/data/bitManipulation-interview-questions">all 12 answers</a></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 9. What are some real world use cases of the bitwise operators?</h2></div> <div>
    👉🏼 Check
    <a href="https://devinterview.io/data/bitManipulation-interview-questions">all 12 answers</a></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 10. What are the advantages of using bitwise operations?</h2></div> <div>
    👉🏼 Check
    <a href="https://devinterview.io/data/bitManipulation-interview-questions">all 12 answers</a></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 11. What is difference between &gt;&gt; and &gt;&gt;&gt; operators?</h2></div> <div>
    👉🏼 Check
    <a href="https://devinterview.io/data/bitManipulation-interview-questions">all 12 answers</a></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 12. Flip k least significant bits in an integer</h2></div> <div>
    👉🏼 Check
    <a href="https://devinterview.io/data/bitManipulation-interview-questions">all 12 answers</a></div> <br><br></div> <div data-v-5e9078c0="" class="end"></div> <br data-v-5e9078c0="">
    Thanks 🙌 for reading and good luck on your next tech interview!
    <br data-v-5e9078c0="">
    Explore 3800+ dev interview question here 👉
    <a data-v-5e9078c0="" href="https://devinterview.io/">Devinterview.io</a></div> <!----></div>
