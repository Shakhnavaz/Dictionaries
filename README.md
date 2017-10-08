# Dictionaries
cars = {
	"Volkswagen", "Lada", "Shevrolet", \
	"Toyota", "Nissan", "Ferrari", \
	"Range Rover", "Suzuki", "Mitsubishi", \
	"Hyundai", "Lamborghini", "Volga"
}
print(cars)
russian_cars = {
	"Lada", "VAZ", "Gazel", "Volga"
}
print("---------------------------------------------")
print(cars & russian_cars)
print("---------------------------------------------")
print(cars | russian_cars)
print("---------------------------------------------")
print(cars - russian_cars)
print("---------------------------------------------")
print(russian_cars - cars)
print("---------------------------------------------")
print(cars ^ russian_cars)
print("=============================================")
countries = {
	"Russia": ("Moscow", "Krasnodar", "Makhachkala"),
	"USA": ("Washington", "New-York", "California"),
	"England": ("London", "Bournmouth", "Liverpool")
}
print(countries["England"])
