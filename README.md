# FOSS-LAB
ch=1
while[$ch -eq 1]
do
echo " enter two value"
read a b
echo "1-addition\n 2-subraction\n 3-multiplication\n 4-division"
echo  "enter option"
read op
casse $op in
	1)c= ` expr $a+$b `
	echo "the sum of two numbers is $c"
	;;
	2)c= ` expr $a-$b `
	echo "the difference of two numbers is $c"
	;;
	3)c= ` expr $a\*$b `
	echo "the multiplication of two numbers is $c"
	;;
	1)c= ` expr $a/$b `
	echo "the division of two numbers is $c"
	;;
	echo "enter a valid option 1-4"
	;;
esac
echo "enter choice to repeat\n 1-yes\n another value-no"
read ch 
done
