select sum(amount) as total_fees
from finance_fees
where year(payment_date)=2023;
