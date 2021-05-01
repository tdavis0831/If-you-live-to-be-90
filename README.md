# If-you-live-to-be-90
Days, weeks and months left in your life if you live to be 90 years old (calculator)

player_age= int(input("How old are you?: "))


player_age_days = player_age*365
player_age_weeks= player_age*52
player_age_months=player_age*12
total_days=90*365
total_weeks=90*52
total_months=90*12


days_left= total_days-player_age_days
weeks_left=total_weeks-player_age_weeks
months_left=total_months-player_age_months


print(f"You have {days_left} days, {weeks_left} weeks, {months_left} months left")
