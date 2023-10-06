NET SALARY CALCULATOR
The program's major task is to calculate an individual's Net salary by getting the inputs of basic salary 
and benefits and then deducting the PAYE, NHIF, and NSSF. Thus, Net Pay = Gross Pay - (PAYE + NHIF + NSSF).
The program is cognizant of the updated tax rates as per the Aren Document. It will also subract the housing 
levy as per the govt requirements from 1st Jul 2023.
The housing levy is 1.5 per cent of the gross pay. Thus, Net pay = Gross Pay - (PAYE + NHIF + NSSF) - (Gross Pay * 0.015).


PAYE CALCULATIONS
If an employee earns up to 24,000, the tax rate is 10%.
elseif salaries between 24001 and 32,333, the tax rate is 25%.
elseif salaries between 32,334 and 500,000, the tax rate is 30%.
elseif salaries between 500,001 and 800,000, the tax rate is 32%.
else salaries above 800,001 are charged at 35%.



NHIF CALCULATIONS

If an employee earns upto 5,999, the NHIF is 150
else if an employee earns between 6,000 and 7,999, the NHIF is 300	
else if an employee earns between 8,000 and 11,999, the NHIF is 400	
else if an employee earns between 12,000 and 14,999, the NHIF is 500	
else if an employee earns between 15,000 and 19,999, the NHIF is 600	
else if an employee earns between 20,000 and 24,999, the NHIF is 750
else if an employee earns between 25,000 and 29,999, the NHIF is 850	
else if an employee earns between 30,000 and 34,999, the NHIF is 900	
else if an employee earns between 35,000 and 39,999, the NHIF is 950
else if an employee earns between 45,000 and 49,999, the NHIF is 1,100
else if an employee earns between 50,000 and 59,999, the NHIF is 1,200
else if an employee earns between 60,000 and 69,999, the NHIF is 1,300
else if an employee earns between 70,000 and 79,999, the NHIF is 1,400
else if an employee earns between 80,000 and 89,999, the NHIF is 1,500
else if an employee earns between 90,000 and 99,999, the NHIF is 1,600
else for an employee that earns 100,000 and above, the NHIF is 1,700.


NSSF CALCULATIONS
If an employee earns up to 5,999, the NHIF deduction is 6% of gross pay: (gross salary * 0.06)
else if an employee earns between 6,000 and 18,000, the NHIF deduction is (gross salary-6000)*0.06.
else, salaries above 18,001 are charged at gross (gross salary-18000)* 0.06

HOUSING LEVY CALCULATIONS


COMPUTATIONS
let netPay = grossSalary - (PAYE + NHIF + NSSF + Housing Levy)
console.log(grossSalary);
console.log(netpay);

function calculateNetPay(NSSF) {
    return (gross salary-NSSF)
}
The program will the compute all the deductions and store them in variables for ease of retrieval. 	 
