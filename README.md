# Merge Sort Project

## Sorting Project 2

### [16,21,11,8,12,22] -> Merge Sort

* Write the stages of the above array according to the sorting type

* Write the Big-O notation 
---

# Answers

<table>
<tr>
<th width="100"></th>
<th width="100">[16,21,11,8,12,22]</th>
<th width="100"></th>
</tr>
<tr>
    <td width="100">First, we divide on two</td>
    <td>16,21,11</td>
    <td>8,12,22</td>
    </tr>
    <tr>
        <td>After dividing them in half, we sort them among themselves</td>
        <td align="end">16</td>
        <td>21,11</td>
        <td>8,12</td>
        <td>22</td>
    </tr>
    <tr>
        <td>We repeat the process</td>
        <td align="center">16</td>
        <td>21</td>
        <td>11</td>
        <td>8</td>
        <td>12</td>
        <td>22</td>
    </tr>
    <tr>
    <td>Now, we are sorting</td>
    <td align="center">16</td>
    <td>11,21</td>
    <td>8,12</td>
    <td>22</td>
    </tr>
<tr>
<td>We continue to sort and combine</td>
<td>11,16,21</td>
<td>8,12,22</td>
</tr>
<tr>
<td>Final sorting and combine</td>
<td>8,11,12,16,21,22</td>
</tr>
</table>

---
## Big-O notation

* 16 11,21 -> n

* 2^x = n -> x=logn

* O(nlogn)

 