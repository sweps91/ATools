ATools = Analytical Tools
import ATools as at
Use info()

ATools version: 0.8.0 (December 2021)
Created by sweps91 (March 2021)

:: THE FUNCTIONS LIST ::

01 --- analyse_num_list(num_list) = Analysing num list
02 --- append_currency(list_of_list, currency) = Take int, creates str, put currency and space between each three nums
03 --- change(list_of_values, rounded=0) = Count change: index 1 - index 0; i 2 - i 1 etc.
04 --- change_fl(list_of_values, rounded=0) = Count difference between last and first item in the list
05 --- change_operator(list_of_lists, rounded=0, first_last=False) = This operator combine change functions
06 --- class WebCall = Working with urls; using requests module
07 --- csv_reader(filename, encoding) =  Reading csv file and making the lists
08 --- csv_writer (filename, list_of_labels, list_of_lists) = Creating csv file
09 --- cumulation(list_of_lists, rounded=0) = Count cumulation in the list(s)
10 --- data_shortcut (list_of_lists, jump=2, start_from_end=True, rounded=2) = Create smaller dataset from the big one
11 --- decrease_or_increase_numbers (list_of_lists, operation_number, increase=False, rounded=0) = Numbers in each list increased or decreased by operation_number
12 --- dictator(list_of_lists, reverse=False, sorted_by_keys=False) = Take lists - create dictionary and sort; default sort by values
13 --- download_csv_file(url, filename) = Paste url of csv file and it will be downloaded
14 --- edit_num_format(list_of_values, crash_sign) = Edit nums from non transforable format to trasformable format
15 --- excel_reader(filename, sheet_name, list_feed_column=False, if_cell_none, remove_string=False, len_columns=None) = Read data from xlsx
16 --- excel_writer(filename, list_of_labels, list_of_lists, write_lables=True) = Write data to xlsx
17 --- find_data_in_range(list_of_values, start, end) = Find specific data in range of bigger dataset
18 --- find_data_in_range_operator(list_of_lists, keyword, start, end, locators=[1,2,3], rounded=0) = Shortcut operator for searching in the dataset in range
19 --- find_dataset_in_range(list_of_lists, list_of_keywords, start, end, locators=[1,2,3], rounded=0) = Upgraded func find_data_in_range - you can search for list of keywords
20 --- find_indexes(list_of_values, keyword, return_all=False) = Search in large dataset for keyword and find out index position
21 --- find_indexes_in_range(list_of_values, start, end) = Find indexes in specific range
22 --- find_labels(list_of_labels) = Find labels in dataset and avoid to duplicate
23 --- find_rows(list_of_lists, list_of_labels, reshape=False, sliced=None,) = Find the row in the dataset; searchind according to list_of_labels
24 --- for_string_in_range(first_str, second_str, start, end, space=1) = Creating desired string with nums
25 --- list_float(list_of_values, no_float_remove=False) = Creating list of float nums
26 --- list_from_index(list_of_lists, index) = Creating new list from given index in lists
27 --- list_from_indexes_and_sum_division(list_of_lists, index_range=None, rounded=1) = Lists_from_indexes + lists_sum_division
28 --- list_int(list_of_values, no_int_remove=False) = Creating list of integers
29 --- list_operator (num_list, operation_num, operator, rounded=1) = num_list[i] operator (default = *) operation_num
30 --- list_str(list_of_values) = Creating list of string
31 --- list_sum_division(list_of_values, rounded=1) = Sum of nums divided by len of list
32 --- list_to_dict_sort_and_back (list_one, list_two, reverse=False) = Take two lists - create dictionary - sort values - create two list sorted according values
33 --- list_to_lists(list_of_values, num_of_lists) = Transform one data list to more lists
34 --- lists_dict_sort(list_of_lists, reverse=False) = Take lists - create dictionary - SORT BY VALUES - !SORTING LIST = INDEX 1!
35 --- lists_from_indexes(list_of_lists, index_range=None) = Create lists in list from indexes (columns)
36 --- lists_function_operator(list_of_lists, func_name_without_brackets) = Take function for one list and extend it for lists
37 --- lists_function_operator_integrated(many predefined kwargs) = Take function for one list and extend it for lists
38 --- lists_sum(list_of_lists, rounded=2) = Take lists and count sum of each list
39 --- lists_sum_division(*args, rounded=1) = Take the lists and count average
40 --- lists_to_list(list_of_values) = Nested lists transform to the simple list
41 --- median(list_of_values) = Median, or 50th percentile, of grouped data
42 --- modulo(a_num, b_num) = Counting modulo and floor division; a_num devided by b_num
43 --- months_cz_list(start, end, space=1) = Creating months CZ list
44 --- months_num_list(start, end, space=1) = Creating months num list
45 --- ordered_lists(list_of_lists, reverse=True) = Take lists - create dictionary - SORT BY KEYS - !SORTING LIST = INDEX 0!
46 --- per_population (values_list, population_list, per_population=1_000, rounded=0, reverse=False) = Values devided per population
47 --- per_population_in_time(list_of_values_lists, list_of_population_lists, per_pop=1_000, rounded=0, reverse=False) = per_population extended to counting in time
48 --- percent_change(list_of_values, rounded=1) = Create the list of the percent change
49 --- percent_change_choice(list_of_values, present_index, past_index, rounded=1) = Create the list of the percent change between two choiced numbers (indexes)
50 --- percent_change_fl(list_of_values, rounded=1) = Create the list of the percent change between the first and the last item
51 --- percent_change_operator(list_of_lists, rounded=1, first_last=False, choice=None, space=None, skip=None) = This operator combine percent_change functions
52 --- percent_change_skip(list_of_values, skip, rounded=1) = Create the list of the percent change with skip range [skip = 4; past = index -5, present = index -1]
53 --- percent_change_space(list_of_values, space=2, rounded=1) = Create the list of the percent change with specified space [space = 4; past = index 0, present = index 4]
54 --- percent_change_two_lists = Percent changes between values in two lists
55 --- percent_layout(list_of_lists, rounded=1) = Percent layout inside the lists
56 --- percent_layout_in_more_lists (list_of_lists, rounded=1) = Percent layout between the lists in the index possitions.
57 --- percent_operation(A, B, A_percent=100, B_percent=False) = Percent operation - find the unknown
58 --- print_item_index(list_with_items) = Print index of item in the list
59 --- print_not_found(list_of_lists, list_of_labels) = Find if label/key is not in the lists
60 --- print_table(list_of_lists, reshape=False) = Print data in the lists
61 --- quartal_list(start, end, space=1) = Creating quartal list
62 --- remove_items(list_of_items, list_of_removing_items, remove_by_index=False) = Remove desired items from list
63 --- remove_letters_from_string(list_of_values) = Take the list and from each string remove letters
64 --- remove_string_from_list(list_of_values) = Remove strings from list
65 --- remove_string_from_lists(list_of_lists) = Remove strings from lists
66 --- reshape(list_of_lists, index_range=None) = Same fn as lists_from_indexes - only renamed for faster using
67 --- rounder(list_of_lists, rounded=0, floating=True, remove_string=False) = Creating the new lists of the rounded numbers
68 --- search_html(url, find, attrs={'class':'container'}, selected=None, data_format) = Searching data in the html page
69 --- test_shape(*args, lol=None, len_num=None) = Testing shape; lol = list of list
70 --- text_analyse(analysed_list, print_items=False, sliced=None, len_pass=1, unwanted=True, unwanted_list=None, lower_case=True) = Analyse list with strings
71 --- tips() = Shortcut tips
72 --- today_date() = Return today date
73 --- two_lists_difference (List_A, List_B, rounded=1) = Values from List_A minus values from List_B = counting difference
74 --- two_lists_difference_operator(A_list_of_lists, B_lists_of_lists, percent=False, rounded=0) = Using two_lists_difference + percent_change_two_lists
75 --- txt_reader (filename, split=True) = Read txt files
76 --- unpack_list(list) = Unpack packed lists
77 --- without_currency(list_of_values, rounded=1) = Only nums, without currency = 40Kč to 40

Number of functions: 77

ATools version: 0.8.0 (December 2021)
Created by sweps91 (March 2021)
More than 1700 lines of code
