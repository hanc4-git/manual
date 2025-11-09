# **xrd bruker d8 advance manual**
UNLV\
the new version is available on [GitHub](https://github.com/hanc4-git?tab=repositories).

## reservation
please contact the **administrator**

## materials
gloves, spatulas, mortar and pestle, methanol *(CH<sub>4</sub>)* or ethanol *(C<sub>2</sub>H<sub>6</sub>O)*

## [bruker](https://www.bruker.com/en/products-and-solutions/diffractometers-and-x-ray-microscopes/x-ray-diffractometers/d8-advance-family/d8-advance.html)
1. push **Open Door** button
> open and close door very **carefully**. if alarm, please contact the **administrator**

2. sample mount

## [diffrac plus xrd commander](https://www.bruker.com/en/products-and-solutions/diffractometers-and-x-ray-microscopes/x-ray-diffractometers/diffrac-suite-software/diffrac-measurement-center.html)
### setup
1. **Jobs**
2. **Create Jobs**
3. **Position #**
4. **Sample ID**
5. open **Parameter File**\
`DIFFDAT1\DQL files\.dql`\
`rotation lynxeye general xrd 0.01 120 min 10-90.dql`
>rotation, lynxeye, general, xrd, scan speed, time, degree

6. create *file name* and save raw *(.raw)* data
7. open **script**\
`DIFFPLUS\MeasureV4.vbs`

8. select **QL** mode
9. **Start** and **OK**\

### export
1. `File\Save As\.txt`
2. capture images *(Ctrl+PrtSc)*
