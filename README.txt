""" 
ATools = Analytical Tools
import ATools as at
Use info()
"""
ver = "0.2.2"
verdate = "April 2021"
created = "March 2021"
author = "sweps91"


:: THE FUNCTIONS LIST ::

analyse_num_list(num_list) = Analysing num list
csv_reader(filename, list_of_columns) =  Reading csv file and making the lists
csv_writer (filename, list_of_labels, *lists_of_values) = Creating csv file
decrease_or_increase_numbers (values_list, operation_number, increase=False, rounded=0) = Numbers in list increased or decreased by operation_number
excel_reader(filename, sheet_name, list_feed_column=False, if_cell_none, remove_string=False, len_columns=None) = Read data from xlsx
excel_writer(filename, list_of_labels, list_of_lists, write_lables=True) = Write data to xlsx
for_string_in_range(first_str, second_str, start, end, space=1) = Creating desired string with nums
list_float(list_of_values) = Creating list of float nums
list_from_index(list_of_lists, index) = Creating new list from given index in lists
list_from_indexes_and_sum_division(list_of_lists, index_range, rounded=1) = Lists_from_indexes + lists_sum_division
list_int(list_of_values) = Creating list of integers
list_operator (num_list, operation_num, operator, rounded=1) = num_list[i] operator (default = *) operation_num
list_rounded(list_of_values) = Creating the new list of the rounded numbers
list_str(list_of_values) = Creating list of string
list_sum_division(list_of_values, rounded=1) = Sum of nums divided by len of list
list_to_dict_sort_and_back (list_one, list_two, reverse=False) = Take two lists - create dictionary - sort values - create two list sorted according values
list_to_lists(list_of_values, *name_of_columns) = Transform one data list to more lists
lists_from_indexes(list_of_lists, index_range) = Create lists in list from indexes (columns)
lists_sum_division(*args, rounded=1) = Take the lists and count average
median(list_of_values) = Median, or 50th percentile, of grouped data
modulo(a_num, b_num) = Counting modulo and floor division; a_num devided by b_num
months_cz_list(start, end, space=1) = Creating months CZ list
months_num_list(start, end, space=1) = Creating months num list
per_population (values_list, population_list, per_population=1_000, rounded=0) = Values devided per population
percent_change(list_of_values, rounded=1) = Create the list of the percent change
percent_change_choice(list_of_values, present_index, past_index, rounded=1) = Create the list of the percent change between two choiced numbers (indexes)
percent_change_fl(list_of_values, rounded=1) = Create the list of the percent change between the first and the last item
percent_change_skip(list_of_values, skip, rounded=1) = Create the list of the percent change with skip range [skip = 4; past = index -5, present = index -1]
percent_change_space(list_of_values, space=2, rounded=1) = Create the list of the percent change with specified space [space = 4; past = index 0, present = index 4]
percent_change_two_lists = Percent changes between values in two lists
percent_operation(A, B, A_percent=100, B_percent=False) = Percent operation - find the unknown
print_item_index(list_with_items) = Print index of item in the list
quartal_list(start, end, space=1) = Creating quartal list
remove_string_from_list(list_of_values) = Remove strings from list
remove_string_from_lists(list_of_lists) = Remove strings from lists
test_shape(*args, len_num=None) = Testing shape
tips() = Shortcut tips
two_lists_difference (List_A, List_B, rounded=1) = Values from List_A minus values from List_B = counting difference

Number of functions: 38

ATools version: 0.2.2 (April 2021)
Created by sweps91 (March 2021)

