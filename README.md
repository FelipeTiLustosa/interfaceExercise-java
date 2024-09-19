# Exercício usando interface em java
## Exercise description:
A company wants to automate the processing of its contracts. Processing a contract consists of generating the installments to be paid for that contract, based on the desired number of months.
The company uses an online payment service to pay installments. Online payment services typically charge a monthly interest, as well as a payment fee. For now, the service contracted by the company is Paypal, which applies simple interest of 1% to each installment, plus a payment fee of 2%.
Make a program to read the data of a contract (contract number, contract data, and total contract value). Next, the program must read the number of months for installments in the contract, and then generate records of installments to be paid (data and value), with the first installment being paid one month after the date of the contract, the second installment two months after the contract and so on. See the installment data on the screen.

### Example:
Entre os dados do contrato: <br>
Numero: 8028 <br>
Data (dd/MM/yyyy): 25/06/2018 <br>
Valor do contrato: 600.00 <br>
Entre com o numero de parcelas: 3 <br>
Parcelas: <br>
25/07/2018 - 206.04 <br>
25/08/2018 - 208.08 <br>
25/09/2018 - 210.12 <br>

### Example:
Cálculos (1% juro simples mensal + 2% taxa de pagamento): <br>
Parcela #1: <br>
200 + 1% * 1 = 202 <br>
202 + 2% = 206.04 <br>
Parcela #2: <br>
200 + 1% * 2 = 204 <br>
204 + 2% = 208.08 <br>
Parcela #3: <br>
200 + 1% * 3 = 206 <br>
206 + 2% = 210.12 <br>
