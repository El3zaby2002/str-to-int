# str-to-int

def str_to_int(coulmns):
  df[coulmns] = df[coulmns].str.replace(r'\D', '', regex=True).astype(int)

df["column"] = df["column"].replace("str" ,)
#to replace the value of columns
or
to transfort the type and replace the value

data[''] = data[''].apply(lambda x: float(x.split(' ')[0]))
# apply the lambda function to each element in the specified column, splitting each element by space and taking the first part, then converting it to a float.

df[""] = df[""].str.split("+")
#This method splits each string into a list of substrings wherever the '+' character is encountered. The result is a new column where each cell contains a list of substrings.
 # WE COULD USE .VALUE_COUNTS() WITH LIST TYPE DATA
