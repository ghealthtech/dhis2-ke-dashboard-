import pandas as pd
import streamlit as st
# load dhis2 data
df = pd.read_csv('dhis2_malaria.csv')
st.title("Kenya DHIS2 - Malaria Trends (Demo from MoH attachment experience)")
st.line_chart(df)