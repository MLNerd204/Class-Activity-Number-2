#include <iostream>
#include <iomanip>  // For std::setprecision

int main() {
    
    const double income = 95000.0;  // The total income
    const double estateTaxRate = 0.04;  // Estate tax rate (4%)
    const double countyTaxRate = 0.02;  // County tax rate (2%)

    double estateTax = income * estateTaxRate;

    double countyTax = income * countyTaxRate;

    double totalTax = estateTax + countyTax;

    std::cout << std::fixed << std::setprecision(2);

    std::cout << "Total Sales: $" << income << std::endl;
    std::cout << "Estate Tax: $" << estateTax << std::endl;
    std::cout << "County Tax: $" << countyTax << std::endl;
    std::cout << "Total Tax: $" << totalTax << std::endl;

    return 0;
}

// Income: Set to be $95,000, Estate Tax Rate is valued as (0.04), and County Tax Rate is (0.02). this programming is calculated by estating the 
Tax (Tax = income * estateTaxRate), the County Tax(County Tax: income * countyTaxRate) and the Total Tax(Total Tax: estateTax + countyTax).
It then prints out the total sales, estate tax, county tax, and the total tax with two decimal precision for a better currency estimation.
