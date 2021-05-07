""" 
ATools = Analytical Tools
import ATools as at
Use info()
"""
ver = "0.4.0"
verdate = "May 2021"
created = "March 2021"
author = "sweps91"

ATools = Analytical Tools

:: THE FUNCTIONS LIST ::

1 --- analyse_num_list(num_list) = Analysing num list
2 --- change(list_of_values, rounded=0) = Count change: index 1 - index 0; i 2 - i 1 etc.
3 --- csv_reader(filename, list_of_columns) =  Reading csv file and making the lists
4 --- csv_writer (filename, list_of_labels, *lists_of_values) = Creating csv file
5 --- cumulation(list_of_lists, rounded=0) = Count cumulation in the list(s)
6 --- decrease_or_increase_numbers (values_list, operation_number, increase=False, rounded=0) = Numbers in list increased or decreased by operation_number
7 --- dictator(list_of_lists, reverse=False, sorted_by_keys=False) = Take lists - create dictionary and sort; default sort by values
8 --- edit_num_format(list_of_values, crash_sign=) = Edit nums from non transforable format to trasformable format
9 --- excel_reader(filename, sheet_name, list_feed_column=False, if_cell_none, remove_string=False, len_columns=None) = Read data from xlsx
10 --- excel_writer(filename, list_of_labels, list_of_lists, write_lables=True) = Write data to xlsx
11 --- for_string_in_range(first_str, second_str, start, end, space=1) = Creating desired string with nums
12 --- list_float(list_of_values, no_float_remove=False) = Creating list of float nums
13 --- list_from_index(list_of_lists, index) = Creating new list from given index in lists
14 --- list_from_indexes_and_sum_division(list_of_lists, index_range=None, rounded=1) = Lists_from_indexes + lists_sum_division
15 --- list_int(list_of_values, no_int_remove=False) = Creating list of integers
16 --- list_operator (num_list, operation_num, operator, rounded=1) = num_list[i] operator (default = *) operation_num
17 --- list_str(list_of_values) = Creating list of string
18 --- list_sum_division(list_of_values, rounded=1) = Sum of nums divided by len of list
19 --- list_to_dict_sort_and_back (list_one, list_two, reverse=False) = Take two lists - create dictionary - sort values - create two list sorted according values
20 --- list_to_lists(list_of_values, *name_of_columns) = Transform one data list to more lists
21 --- lists_dict_sort(list_of_lists, reverse=False) = Take lists - create dictionary - SORT BY VALUES - !SORTING LIST = INDEX 1!
22 --- lists_from_indexes(list_of_lists, index_range=None) = Create lists in list from indexes (columns)
23 --- lists_function_operator(list_of_lists, func_name_without_brackets) = Take function for one list and extend it for lists
24 --- lists_function_operator_integrated(many predefined kwargs) = Take function for one list and extend it for lists
25 --- lists_sum(list_of_values, rounded=2) = Take lists and count sum of each list
26 --- lists_sum_division(*args, rounded=1) = Take the lists and count average
27 --- median(list_of_values) = Median, or 50th percentile, of grouped data
28 --- modulo(a_num, b_num) = Counting modulo and floor division; a_num devided by b_num
29 --- months_cz_list(start, end, space=1) = Creating months CZ list
30 --- months_num_list(start, end, space=1) = Creating months num list
31 --- ordered_lists(list_of_lists, reverse=True) = Take lists - create dictionary - SORT BY KEYS - !SORTING LIST = INDEX 0!
32 --- per_population (values_list, population_list, per_population=1_000, rounded=0, reverse=False) = Values devided per population
33 --- percent_change(list_of_values, rounded=1) = Create the list of the percent change
34 --- percent_change_choice(list_of_values, present_index, past_index, rounded=1) = Create the list of the percent change between two choiced numbers (indexes)
35 --- percent_change_fl(list_of_values, rounded=1) = Create the list of the percent change between the first and the last item
36 --- percent_change_skip(list_of_values, skip, rounded=1) = Create the list of the percent change with skip range [skip = 4; past = index -5, present = index -1]
37 --- percent_change_space(list_of_values, space=2, rounded=1) = Create the list of the percent change with specified space [space = 4; past = index 0, present = index 4]
38 --- percent_change_two_lists = Percent changes between values in two lists
39 --- percent_layout(list_of_lists, rounded=1) = Percent layout in the lists
40 --- percent_operation(A, B, A_percent=100, B_percent=False) = Percent operation - find the unknown
41 --- print_item_index(list_with_items) = Print index of item in the list
42 --- print_table(list_of_lists) = Print data in the lists
43 --- quartal_list(start, end, space=1) = Creating quartal list
44 --- remove_items(list_of_items, list_of_removing_items, remove_by_index=False) = Remove desired items from list
45 --- remove_string_from_list(list_of_values) = Remove strings from list
46 --- remove_string_from_lists(list_of_lists) = Remove strings from lists
47 --- rounder(list_of_lists, rounded=0, floating=True, remove_string=False) = Creating the new lists of the rounded numbers
48 --- test_shape(*args, lol=None, len_num=None) = Testing shape; lol = list of list
49 --- text_analyse(analysed_list, print_items=False, sliced=None) = Analyse list with strings
50 --- tips() = Shortcut tips
51 --- two_lists_difference (List_A, List_B, rounded=1) = Values from List_A minus values from List_B = counting difference
52 --- txt_reader (filename, split=True) = Read txt files

Number of functions: 52

ATools version: 0.4.0 (May 2021)
Created by sweps91 (March 2021)
More than 1100 lines of code


