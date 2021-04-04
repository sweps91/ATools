""" 
ATools = Analytical Tools
import ATools as at
Use info()
"""
ver = "0.1.2"
author = "sweps91"


:: THE FUNCTIONS LIST ::

csv_reader(filename, list_of_columns) =  Reading csv file and making the lists
csv_writer (filename, list_of_labels, *lists_of_values) = Creating csv file
for_string_in_range(first_str, second_str, start, end, space=1) = Creating desired string with nums
list_float(list_of_values) = Creating list of float nums
list_from_index(list_of_lists, index) = Creating new list from given index in lists
list_from_indexes_and_sum_division(list_of_lists, index_range, rounded=1) = Lists_from_indexes + lists_sum_division
list_int(list_of_values) = Creating list of integers
list_rounded(list_of_values) = Creating the new list of the rounded numbers
list_sum_division(list_of_values, rounded=1) = Sum of nums divided by len of list
list_to_dict_sort_and_back (list_one, list_two, reverse=False) = Take two lists - create dictionary - sort values - create two list sorted according values
list_to_lists(list_of_values, *name_of_columns) = Transform one data list to more lists
lists_from_indexes(list_of_lists, index_range) = Create lists in list from indexes (columns)
lists_sum_division(*args, rounded=1) = Take the lists and count average
median(list_of_values) = Median, or 50th percentile, of grouped data
modulo(a_num, b_num) = Counting modulo and floor division; a_num devided by b_num
months_cz_list(start, end, space=1) = Creating months CZ list
months_num_list(start, end, space=1) = Creating months num list
percent_change(list_of_values, rounded=1) = Create the list of the percent change
percent_change_choice(list_of_values, present_index, past_index, rounded=1) = Create the list of the percent change between two choiced numbers (indexes)
percent_change_fl(list_of_values, rounded=1) = Create the list of the percent change between the first and the last item
percent_change_skip(list_of_values, skip, rounded=1) = Create the list of the percent change with skip range [skip = 4; past = index -5, present = index -1]
percent_change_space(list_of_values, space=2, rounded=1) = Create the list of the percent change with specified space [space = 4; past = index 0, present = index 4]
percent_operation(A, B, A_percent=100, B_percent=False) = Percent operation - find the unknown
quartal_list(start, end, space=1) = Creating quartal list
test_shape(*args, len_num=None) = Testing shape
tips() = Shortcut tips

Number of functions: 26

ATools version: 0.1.2
Created by sweps91
