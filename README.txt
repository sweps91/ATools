""" 
ATools = Analytical Tools
import ATools as at
Use at.info()
"""
ver = "0.9.2"

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
12 --- def timedelta(time, days=1_000) = count days from time
13 --- dictator(list_of_lists, reverse=False, sorted_by_keys=False) = Take lists - create dictionary and sort; default sort by values
14 --- download_csv_file(url, filename) = Paste url of csv file and it will be downloaded
15 --- edit_num_format(list_of_values, crash_sign) = Edit nums from non transforable format to trasformable format
16 --- excel_reader(filename, sheet_name, list_feed_column=False, if_cell_none, remove_string=False, len_columns=None) = Read data from xlsx
17 --- excel_writer(filename, list_of_labels, list_of_lists, write_lables=True) = Write data to xlsx
18 --- fibonacci_number(stop_num) = Function for counting fibonacci number
19 --- find_data_in_range(list_of_values, start, end) = Find specific data in range of bigger dataset
20 --- find_data_in_range_operator(list_of_lists, keyword, start, end, locators=[1,2,3], rounded=0) = Shortcut operator for searching in the dataset in range
21 --- find_dataset_in_range(list_of_lists, list_of_keywords, start, end, locators=[1,2,3], rounded=0) = Upgraded func find_data_in_range - you can search for list of keywords
22 --- find_in_html(html_data, find, attrs=None, stringed=False) = Searching data in the html code
23 --- find_index(dataset, searching_name, labels=True) = Search the name in labels or in columns or rows
24 --- find_indexes(list_of_values, keyword, return_all=False) = Search in large dataset for keyword and find out index position
25 --- find_indexes_in_range(list_of_values, start, end) = Find indexes in specific range
26 --- find_labels(list_of_labels) = Find labels in dataset and avoid to duplicate
27 --- find_longest(list_of_values) = Find the longest item in the list
28 --- find_rows(list_of_lists, list_of_labels, reshape=False, sliced=None,) = Find the row in the dataset; searchind according to list_of_labels
29 --- find_trend(team_place_list) = Find the trend - count avg from 5 values in the list
30 --- for_string_in_range(first_str, second_str, start, end, space=1) = Creating desired string with nums
31 --- geojson_linestring(path, list_of_coordinates, name_geojson, reverse_lat_lng=False) = Create GeoJSON LineString format
32 --- geojson_multilinestring(path, list_of_lists_with_coordinates, name_geojson, reverse_lat_lng=False) = Create GeoJSON MultiLineString format
33 --- html_selector(html_data, select, text=False, data_index=0) = paste html data - returns selected element
34 --- html_source(url) = paste source html - it returns html code
35 --- list_float(list_of_values, no_float_remove=False) = Creating list of float nums
36 --- list_from_index(list_of_lists, index) = Creating new list from given index in lists
37 --- list_from_indexes_and_sum_division(list_of_lists, index_range=None, rounded=1) = Lists_from_indexes + lists_sum_division
38 --- list_int(list_of_values, no_int_remove=False) = Creating list of integers
39 --- list_operator (num_list, operation_num, operator, rounded=1) = num_list[i] operator (default = *) operation_num
40 --- list_str(list_of_values) = Creating list of string
41 --- list_sum_division(list_of_values, rounded=1) = Sum of nums divided by len of list
42 --- list_to_dict_sort_and_back (list_one, list_two, reverse=False) = Take two lists - create dictionary - sort values - create two list sorted according values
43 --- list_to_lists(list_of_values, num_of_lists) = Transform one data list to more lists
44 --- lists_dict_sort(list_of_lists, reverse=False) = Take lists - create dictionary - SORT BY VALUES - !SORTING LIST = INDEX 1!
45 --- lists_from_indexes(list_of_lists, index_range=None) = Create lists in list from indexes (columns)
46 --- lists_function_operator(list_of_lists, func_name_without_brackets) = Take function for one list and extend it for lists
47 --- lists_function_operator_integrated(many predefined kwargs) = Take function for one list and extend it for lists
48 --- lists_sum(list_of_lists, rounded=2) = Take lists and count sum of each list
49 --- lists_sum_division(*args, rounded=1) = Take the lists and count average
50 --- lists_to_list(list_of_values) = Nested lists transform to the simple list
51 --- median(list_of_values) = Median, or 50th percentile, of grouped data
52 --- modulo(a_num, b_num) = Counting modulo and floor division; a_num devided by b_num
53 --- months_cz_list(start, end, space=1) = Creating months CZ list
54 --- months_num_list(start, end, space=1) = Creating months num list
55 --- nice_data(list_of_values, sign, second_sign=None, on_index=1, break_index=2) = Clear data from larger text strings (eg. in html)
56 --- ordered_lists(list_of_lists, reverse=True) = Take lists - create dictionary - SORT BY KEYS - !SORTING LIST = INDEX 0!
57 --- owid_world_map_data = working with data from our world in data (owid)
58 --- per_population (values_list, population_list, per_population=1_000, rounded=0, reverse=False) = Values devided per population
59 --- per_population_in_time(list_of_values_lists, list_of_population_lists, per_pop=1_000, rounded=0, reverse=False) = per_population extended to counting in time
60 --- percent_change(list_of_values, rounded=1) = Create the list of the percent change
61 --- percent_change_choice(list_of_values, present_index, past_index, rounded=1) = Create the list of the percent change between two choiced numbers (indexes)
62 --- percent_change_fl(list_of_values, rounded=1) = Create the list of the percent change between the first and the last item
63 --- percent_change_operator(list_of_lists, rounded=1, first_last=False, choice=None, space=None, skip=None) = This operator combine percent_change functions
64 --- percent_change_skip(list_of_values, skip, rounded=1) = Create the list of the percent change with skip range [skip = 4; past = index -5, present = index -1]
65 --- percent_change_space(list_of_values, space=2, rounded=1) = Create the list of the percent change with specified space [space = 4; past = index 0, present = index 4]
66 --- percent_change_two_lists = Percent changes between values in two lists
67 --- percent_layout(list_of_lists, rounded=1) = Percent layout inside the lists
68 --- percent_layout_in_more_lists (list_of_lists, rounded=1) = Percent layout between the lists in the index possitions.
69 --- percent_operation(A, B, A_percent=100, B_percent=False) = Percent operation - find the unknown
70 --- picker(list_of_values, start, end, skip) = Pick data from the list - for index in range (start, end, skip)
71 --- print_item_index(list_with_items) = Print index of item in the list
72 --- print_nice_numbers(list_of_numbers) = print list of numbers with separator
73 --- print_not_found(list_of_lists, list_of_labels) = Find if label/key is not in the lists
74 --- print_table(list_of_lists, reshape=False) = Print data in the lists
75 --- quartal_list(start, end, space=1) = Creating quartal list
76 --- remove_items(list_of_items, list_of_removing_items, remove_by_index=False) = Remove desired items from list
77 --- remove_letters_from_string(list_of_values) = Take the list and from each string remove letters
78 --- remove_string_from_list(list_of_values) = Remove strings from list
79 --- remove_string_from_lists(list_of_lists) = Remove strings from lists
80 --- reshape(list_of_lists, index_range=None) = Same fn as lists_from_indexes - only renamed for faster using
81 --- rounder(list_of_lists, rounded=0, floating=True, remove_string=False) = Creating the new lists of the rounded numbers
82 --- search_html(url, find, attrs={'class':'container'}, selected=None, data_format) = Searching data in the html page
83 --- slicer(list_of_values, start, end) = Slice data for each value in the list
84 --- test_shape(*args, lol=None, len_num=None) = Testing shape; lol = list of list
85 --- text_analyse(analysed_list, print_items=False, sliced=None, len_pass=1, unwanted=True, unwanted_list=None, lower_case=True) = Analyse list with strings
86 --- time_time(start_time) = measure time of execution
87 --- timeit(function_to_measure) = function to measure time
88 --- tips() = Shortcut tips
89 --- today_date() = Return today date
90 --- two_lists_difference (List_A, List_B, rounded=1) = Values from List_A minus values from List_B = counting difference
91 --- two_lists_difference_operator(A_list_of_lists, B_lists_of_lists, percent=False, rounded=0) = Using two_lists_difference + percent_change_two_lists
92 --- txt_reader (filename, split=True) = Read txt files
93 --- types(list_of_lists, summary=True, localized=None, reshaped=False) = Explore data types in the lists
94 --- unpack_list(list) = Unpack packed lists
95 --- without_currency(list_of_values, rounded=1) = Only nums, without currency = 40Kč to 40

Number of functions: 95

ATools version: 0.9.2 (September 2022)
Created by sweps91 (March 2021)
More than 2300 lines of code
