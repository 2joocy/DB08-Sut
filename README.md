# DB08-Sut

Made by:
 - Chris Rosendorf
 - Viktor Kim Christiansen
 - William Pfaffe

## 1
**π<sub>customerName, city</sub> σ <sub>
                                    salesRepEmployeeNumber = employeeNumber ∧
                                    officeCode = officeCode ∧
                                    city = city
                                </sub>
(customers x employees x offices)**

## 2
**π<sub>customerName, city</sub> σ <sub>
                                    salesRepEmployeeNumber = employeeNumber, COUNT(employeeNumber) ∧
                                    officeCode = officeCode, COUNT(officeCode) ∧
                                    city = city COUNT(city)
                                </sub>
(customers x employees x offices)**

## 3
**π<sub>customerName, city</sub> σ <sub>
                                    salesRepEmployeeNumber = employeeNumber
                                </sub> (customers ⋈ employees ⋈ offices)**