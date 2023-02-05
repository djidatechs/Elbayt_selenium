from selenium import webdriver
from selenium.webdriver.support.ui import Select
from time import sleep
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as EC
from selenium.webdriver.common.by import By

driver = webdriver.ChromiumEdge()



driver.get("https://elbaytdz.netlify.app/signup")


wait = WebDriverWait(driver, 200)
wait.until(EC.url_to_be("https://elbaytdz.netlify.app/annonces/new"))

sleep(5)

button_1 = driver.find_element(By.CLASS_NAME,"selenium_btn1")

selenium_type = driver.find_element(By.CLASS_NAME,"selenium_type")
selenium_wilaya = driver.find_element(By.CLASS_NAME,"selenium_wilaya")
selenium_commune = driver.find_element(By.CLASS_NAME,"selenium_commune")
selenium_lat = driver.find_element(By.CLASS_NAME,"selenium_lat")
selenium_lng = driver.find_element(By.CLASS_NAME,"selenium_lng")


select_w = Select(selenium_wilaya)
print (select_w)
select_w.select_by_value("16") 
sleep(2)
select_c = Select(selenium_commune)
select_c.select_by_value("558") 
selenium_type.send_keys("selenium_Example")
selenium_lat.send_keys("36.752887")
selenium_lng.send_keys("3.042048")
button_1.click()
sleep(1)



button_2 = driver.find_element(By.CLASS_NAME,"selenium_btn2")

selenium_surface = driver.find_element(By.CLASS_NAME,"selenium_surface")
selenium_price = driver.find_element(By.CLASS_NAME,"selenium_price")

sleep(10)




selenium_surface.send_keys("100")
selenium_price.send_keys("655600")

button_2.click()
sleep(2)


button_3 = driver.find_element(By.CLASS_NAME,"selenium_btn3")

selenium_phone = driver.find_element(By.CLASS_NAME,"selenium_phone")
selenium_description = driver.find_element(By.CLASS_NAME,"selenium_description")

selenium_phone.send_keys("0558713153")
selenium_description.send_keys("selenium_example ")
button_3.click()
sleep(2)


button_4 = driver.find_element(By.CLASS_NAME,"selenium_btn4")
button_4.click()
sleep(2)



title = driver.title

print("Page title:", title)
sleep(15)
driver.quit()
