# time_helper for codeigniter developers.

### drop this time_helper.php in your helper folder inside application

by [lloricode](https://github.com/lloricode)

```php

$this->load->helper('time');
print_r(time_list());
                
Array
(
    [] => Time
    [06:00] => 06:00 AM
    [06:30] => 06:30 AM
    [07:00] => 07:00 AM
    [07:30] => 07:30 AM
    [08:00] => 08:00 AM
    [08:30] => 08:30 AM
    [09:00] => 09:00 AM
    [09:30] => 09:30 AM
    [10:00] => 10:00 AM
    [10:30] => 10:30 AM
    [11:00] => 11:00 AM
    [11:30] => 11:30 AM
    [12:00] => 12:00 PM
    [12:30] => 12:30 PM
    [13:00] => 01:00 PM
    [13:30] => 01:30 PM
    [14:00] => 02:00 PM
    [14:30] => 02:30 PM
    [15:00] => 03:00 PM
    [15:30] => 03:30 PM
    [16:00] => 04:00 PM
    [16:30] => 04:30 PM
    [17:00] => 05:00 PM
    [17:30] => 05:30 PM
    [18:00] => 06:00 PM
    [18:30] => 06:30 PM
)

//other functions

convert_24_to_12hrs($hr24 = NULL)
convert_12_to_24hrs($hr12 = NULL)
convert_24hrs_to_seconds($hr24)



```
