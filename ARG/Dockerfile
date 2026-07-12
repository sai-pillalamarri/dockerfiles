FROM almalinux:9

ARG employee_name="sai" \
    employee_id="57362" \
    salary=55000

ENV emp_name=${employee_name} \
    emp_id=${employee_id} \
    emp_salary=${salary}

RUN echo "Employee Name: ${employee_name}  ID: ${employee_id}  Salary: ${salary}"

CMD ["sleep","500"]