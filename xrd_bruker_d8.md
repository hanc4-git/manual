# **xrd bruker d8 advance manual**
UNLV\
the new version is available on [GitHub](https://github.com/hanc4-git?tab=repositories).

## reservation
please contact the **administrator**

## materials
gloves, spatulas, mortar and pestle, methanol *(CH<sub>4</sub>)* or ethanol *(C<sub>2</sub>H<sub>6</sub>O)*

## [bruker](https://www.bruker.com/en/products-and-solutions/diffractometers-and-x-ray-microscopes/x-ray-diffractometers/d8-advance-family/d8-advance.html)
1. push **Open Door (green square)** button
> open and close door very **carefully**. if alarm, please contact the **administrator**

2. sample mount

## [diffrac plus xrd commander](https://www.bruker.com/en/products-and-solutions/diffractometers-and-x-ray-microscopes/x-ray-diffractometers/diffrac-suite-software/diffrac-measurement-center.html)
### setup
1. run **DIFFRAC plus XRD Commander**
2. **Jobs**
3. **Create Jobs**
4. **Position #**
5. **Sample ID**
6. open **Parameter File**
7. `DIFFDAT1 > DQL files > *.dql`\
  `rotation lynxeye general xrd 0.01 120 min 10-90.dql`
   > rotation, lynxeye, general, xrd, scan speed, time, degree

8. create *file name* and save raw *(***.raw)* data
9. open **script**
10. `DIFFPLUS > MeasureV4.vbs`
11. select **QL** mode
12. **Start** and **OK**

### export
1. `File > Save As > *.txt`
2. capture images *(Ctrl+PrtSc)*

## troubleshooting
1. if power turned off, press **green circle** button
2. run **D8 tools**
> diagnose software

  1. open **STATUS-file**
  2. `My Documents > Status > *.sts`
  3. check red alarm on whole category
  4. if something wrong, please contact the **administrator**

3. run **DIFFRAC plus XRD Commander**
  1. check degree
  > Theta 30<sup>o</sup> and 2Theta 60<sup>o</sup>

  2. if not match, type *degree values* in the blank box
  3. click **Int Drives**
  4. check **Power Voltage**
  > Default values = 20*kV, 5*mA\
  > when xrd running, increase power up to **40*kV,** **40*mA** gradually

  6. if not going up, stop jobs and set power up again
  7. type *kV values* in the blank box
  8. click **Set**
  > when xrd running, increase power **5-10*kV,** **5-10*mA** each time

4. if something wrong, please contact the **administrator**
