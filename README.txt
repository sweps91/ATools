""" 
ATools = Analytical Tools
import ATools as at
Use info()
"""
ver = "0.5.7"
verdate = "May 2021"
created = "March 2021"
author = "sweps91"

ATools = Analytical Tools

:: THE FUNCTIONS LIST ::

01 --- analyse_num_list(num_list) = Analysing num list
02 --- change(list_of_values, rounded=0) = Count change: index 1 - index 0; i 2 - i 1 etc.
03 --- change_fl(list_of_values, rounded=0) = Count difference between last and first item in the list
04 --- change_operator(list_of_lists, rounded=0, first_last=False) = This operator combine change functions
05 --- csv_reader(filename, list_of_columns) =  Reading csv file and making the lists
06 --- csv_writer (filename, list_of_labels, *lists_of_values) = Creating csv file
07 --- cumulation(list_of_lists, rounded=0) = Count cumulation in the list(s)
08 --- data_shortcut (list_of_lists, jump=2, start_from_end=True, rounded=2) = Create smaller dataset from the big one
09 --- decrease_or_increase_numbers (list_of_lists, operation_number, increase=False, rounded=0) = Numbers in each list increased or decreased by operation_number
10 --- dictator(list_of_lists, reverse=False, sorted_by_keys=False) = Take lists - create dictionary and sort; default sort by values
11 --- edit_num_format(list_of_values, crash_sign) = Edit nums from non transforable format to trasformable format
12 --- excel_reader(filename, sheet_name, list_feed_column=False, if_cell_none, remove_string=False, len_columns=None) = Read data from xlsx
13 --- excel_writer(filename, list_of_labels, list_of_lists, write_lables=True) = Write data to xlsx
14 --- find_data_in_range(list_of_values, start, end) = Find specific data in range of bigger dataset
15 --- find_data_in_range_operator(list_of_lists, keyword, start, end, locators=[1,2,3], rounded=0) = Shortcut operator for searching in the dataset in range
16 --- find_dataset_in_range(list_of_lists, list_of_keywords, start, end, locators=[1,2,3], rounded=0) = Upgraded func find_data_in_range - you can search for list of keywords
17 --- find_indexes(list_of_values, keyword, return_all=False) = Search in large dataset for keyword and find out index position
18 --- find_indexes_in_range(list_of_values, start, end) = Find indexes in specific range
19 --- find_labels(list_of_labels) = Find labels in dataset and avoid to duplicate
20 --- for_string_in_range(first_str, second_str, start, end, space=1) = Creating desired string with nums
21 --- list_float(list_of_values, no_float_remove=False) = Creating list of float nums
22 --- list_from_index(list_of_lists, index) = Creating new list from given index in lists
23 --- list_from_indexes_and_sum_division(list_of_lists, index_range=None, rounded=1) = Lists_from_indexes + lists_sum_division
24 --- list_int(list_of_values, no_int_remove=False) = Creating list of integers
25 --- list_operator (num_list, operation_num, operator, rounded=1) = num_list[i] operator (default = *) operation_num
26 --- list_str(list_of_values) = Creating list of string
27 --- list_sum_division(list_of_values, rounded=1) = Sum of nums divided by len of list
28 --- list_to_dict_sort_and_back (list_one, list_two, reverse=False) = Take two lists - create dictionary - sort values - create two list sorted according values
29 --- list_to_lists(list_of_values, num_of_lists) = Transform one data list to more lists
30 --- lists_dict_sort(list_of_lists, reverse=False) = Take lists - create dictionary - SORT BY VALUES - !SORTING LIST = INDEX 1!
31 --- lists_from_indexes(list_of_lists, index_range=None) = Create lists in list from indexes (columns)
32 --- lists_function_operator(list_of_lists, func_name_without_brackets) = Take function for one list and extend it for lists
33 --- lists_function_operator_integrated(many predefined kwargs) = Take function for one list and extend it for lists
34 --- lists_sum(list_of_lists, rounded=2) = Take lists and count sum of each list
35 --- lists_sum_division(*args, rounded=1) = Take the lists and count average
36 --- lists_to_list(list_of_values) = Nested lists transform to the simple list
37 --- median(list_of_values) = Median, or 50th percentile, of grouped data
38 --- modulo(a_num, b_num) = Counting modulo and floor division; a_num devided by b_num
39 --- months_cz_list(start, end, space=1) = Creating months CZ list
40 --- months_num_list(start, end, space=1) = Creating months num list
41 --- ordered_lists(list_of_lists, reverse=True) = Take lists - create dictionary - SORT BY KEYS - !SORTING LIST = INDEX 0!
42 --- per_population (values_list, population_list, per_population=1_000, rounded=0, reverse=False) = Values devided per population
43 --- per_population_in_time(list_of_values_lists, list_of_population_lists, per_pop=1_000, rounded=0, reverse=False) = per_population extended to counting in time
44 --- percent_change(list_of_values, rounded=1) = Create the list of the percent change
45 --- percent_change_choice(list_of_values, present_index, past_index, rounded=1) = Create the list of the percent change between two choiced numbers (indexes)
46 --- percent_change_fl(list_of_values, rounded=1) = Create the list of the percent change between the first and the last item
47 --- percent_change_operator(list_of_lists, rounded=1, first_last=False, choice=None, space=None, skip=None) = This operator combine percent_change functions
48 --- percent_change_skip(list_of_values, skip, rounded=1) = Create the list of the percent change with skip range [skip = 4; past = index -5, present = index -1]
49 --- percent_change_space(list_of_values, space=2, rounded=1) = Create the list of the percent change with specified space [space = 4; past = index 0, present = index 4]
50 --- percent_change_two_lists = Percent changes between values in two lists
51 --- percent_layout(list_of_lists, rounded=1) = Percent layout in the lists
52 --- percent_operation(A, B, A_percent=100, B_percent=False) = Percent operation - find the unknown
53 --- print_item_index(list_with_items) = Print index of item in the list
54 --- print_table(list_of_lists) = Print data in the lists
55 --- quartal_list(start, end, space=1) = Creating quartal list
56 --- remove_items(list_of_items, list_of_removing_items, remove_by_index=False) = Remove desired items from list
57 --- remove_string_from_list(list_of_values) = Remove strings from list
58 --- remove_string_from_lists(list_of_lists) = Remove strings from lists
59 --- rounder(list_of_lists, rounded=0, floating=True, remove_string=False) = Creating the new lists of the rounded numbers
60 --- test_shape(*args, lol=None, len_num=None) = Testing shape; lol = list of list
61 --- text_analyse(analysed_list, print_items=False, sliced=None, len_pass=1, unwanted=True, unwanted_list=None, lower_case=True) = Analyse list with strings
62 --- tips() = Shortcut tips
63 --- two_lists_difference (List_A, List_B, rounded=1) = Values from List_A minus values from List_B = counting difference
64 --- two_lists_difference_operator(A_list_of_lists, B_lists_of_lists, percent=False, rounded=0) = Using two_lists_difference + percent_change_two_lists
65 --- txt_reader (filename, split=True) = Read txt files
66 --- without_currency(list_of_values, rounded=1) = Only nums, without currency = 40Kč to 40

Number of functions: 66

ATools version: 0.5.7 (May 2021)
Created by sweps91 (March 2021)
More than 1500 lines of code

