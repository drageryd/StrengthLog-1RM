# Strength Log PB

In StrengthLog settings, export your data as csv and place in this directory

Change the input to `parse_strengthlog_workouts` to your file name

`print_excercise_names` will output all excercises you have trained, choose one as input to `extract_pbs_by_reps`

See the data visualized as every PB you have acheived per rep, the more green the graph the newer the PB.

Example (Bench Press):

![alt text](image.png)

## Dependencies

`numpy`
`matplotlib`

## Notes

There may be language dependent things hardcoded into this that have to be changed.

For example: `Övning, ` and `Datum` that could be different if the language anything other than Swedish.
