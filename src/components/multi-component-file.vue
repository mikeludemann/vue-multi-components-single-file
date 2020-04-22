<script>

export const ModernTable = {
	props: {
		id: {
			type: String,
			default: "test-table"
		}
	},
	render(){
		return (
			<div>
				<table id={this.id}>
					{this.$slots.default}
				</table>
			</div>
		)
	}
};

export const ModernRow = {
	props: {

	},
	render(){
		return (
			<tr>
				{this.$slots.default}
			</tr>
		)
	}
};

export default ModernTable

</script>

<style scoped lang="scss">
	.multi-component-file {

	}
</style>
