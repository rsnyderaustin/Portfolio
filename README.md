# Austin's Portfolio
Welcome to my data portfolio! Listed below are a variety of projects showcasing my skills in the data field.
My resume is available in the project files listed above. 

'
select distinct p.product_id, pcnt.product_category_name_english, p.product_photos_qty, p.product_weight_g,
p.product_length_cm, p.product_height_cm, p.product_width_cm
from public.product_category_name_translation pcnt 
inner join public.products p
	on pcnt.product_category_name = p.product_category_name 
 '
