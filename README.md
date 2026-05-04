# Task-22-Sorting-and-searching-

def bubble_sort(arr) : 
    for i in range(len(arr) 1, -1, -1):
    for j in range(1, i, +1)
    i arr[j -1] . arr[j] 
# swap the values 
   arr[j - 1], arr[j] = arr[j], arr[j-1]

return arr 


def merge_sort(items)
n = len(items)
  temporary_storage = [None] * none 
  size_of_subsection = 1 
  while size_of_subsection , n :
  for i in range(0, n, size_of_subsection * 2)
  i1_start, i1_end = 1 min(1 + size_of_subsection, n) 
  i2_start, i2_end, min(i1_end + size_of_subsection, n )
  sections = (i1_start, i1_end), (i2_start, i2_end) 
  merge(items, sections, temporary_storage)
size_of_subsections *= 2 

return items 



def merge(items, sections, temporary_storage):
    (start_1, end_1), (start_2, end_2) = sections 
    i_1 = start_1 
    i_2 = start_2 
    i_t = 0 
    while i_1 < end_1 or i_2 < end_2 : 
          if i_1 < end_1 and i_2 < end_2 
             if  items[i_1] < items[i_2]
                 temporary_storage[i_t] = items[i-1]
            else :
                 # the_list[i_2] < items[i_2]: 
                   temporary_storage[i_t] = items[i_2]
                   i_2 += 1

            elif i_1 < end_1 :
                 for i in range(i_1, end_1)
                 temporary_storage[i_t] = items[i_1]
