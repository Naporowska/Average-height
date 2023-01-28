import statistics

student_heights = input("Enter students heights:\n")

heights_list = student_heights.split(", ")
print(heights_list)

heights_list_int = []
for n in heights_list:
    heights_list_int.append(int(n))

print(heights_list_int)

print(round(statistics.mean(heights_list_int), 2))

heights_sum = 0
for n in heights_list_int:
    heights_sum += n

print(round(heights_sum / len(heights_list_int), 2))
