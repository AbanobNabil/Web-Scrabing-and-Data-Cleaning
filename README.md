# Web-Scrabing-and-Data-Cleaning
Web Scrabing and Data Cleaning for Wuzzuf Web Site
\\\ info for function\\\
1- extract_numeric_and_hyphen :  Extract only numeric values and hyphens from the input string.
    Args:
        input_string (str): The string from which to extract numeric values and hyphens.
    Returns:
        str: The cleaned string containing only numeric values and hyphens.

2- clean_expriance : Clean up the 'Experience years' data by checking if the value contains a hyphen ("-")
    and both parts of the split result are equal. If so, it returns only one part;
    otherwise, it leaves the original 'Experience years' value unchanged.
   a Args:
        exp (str): The 'Experience years' value to be cleaned.
    Returns:
        str: The cleaned 'Experience years' value.

3- convert_single_to_range : Converts single values in the list to range format by matching them to existing ranges.
    Args:
        data (list): A list of values where single values might be converted to ranges.
    Returns:
        list: The modified list with single values converted to ranges and sorted.

4- clean_skils : Clean up the skills by removing text after forward slashes.
    Args:
        skills (str): The job title string to be cleaned.
    Returns:
        str: The cleaned skills string.
